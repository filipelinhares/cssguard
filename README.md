# CSS Guard
> An easy way to test your CSS.

## Install
```
npm install --save-dev cssguard
```

## Usage
1. `cd into-my-project`
2. `mkdir test && cd $_ && touch test.html`
3. Install with npm commands
4. Load the csstest.css file into your html.

  ```css
  @import '../node_modules/cssguard/cssguard.css';
  ```
  or
  ```html
  <link rel="stylesheet" href="../node_modules/cssguard/dist/cssguard.css">
  ```
5. Create your test suite

  ```html
  <main class="test-suite">
    <h1 class="test-suite-title">Project name</h1>
    <section>
      <h1 class="test-module">Test section</h1>
      <h3 class="test-it">The test <code>.example-code</code></h3>
      <div class="test-run">
        <p>Some test here</p>
      </div>
    </section>
  </main>
  ```
6. Test your component :D

## API
- `.test-suite`
- `.test-suite-title`
- `.test-module`
- `.test-it`
- `.test-run`

## License
[MIT](LICENSE.md) © Filipe Linhares
