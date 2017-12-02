# \<ud-stepper\>

Material Design:
[Steppers](https://material.io/guidelines/components/steppers.html)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="ud-stepper.html">
    <style is="custom-style" include="demo-pages-shared-styles">
      ud-step {
        height: 250px;
        --ud-step-content-style: {
          background-color: rgba(0, 0, 0, .1);
          padding: 5px;
          color: rgba(0, 0, 0, 0.8);
        }
      }
      .demo-actions {
        display: flex;
        flex-direction: row;
        padding: 10px 0px 10px 0px;
        align-items: center;
        justify-content: space-between;
      }

      .demo-actions .buttons {
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
      }

      .demo-actions .buttons .reset {
        background-color: var(--paper-pink-400);
        color: white;
      }

      .demo-actions .buttons .toggle {
        background-color: var(--paper-indigo-400);
        color: white;
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->

```html
<ud-stepper linear>
    <ud-step title="Step 1">
      <div slot="content">Step 1 Content</div>
    </ud-step>
    <ud-step title="Step 2 with long title">
      <div slot="content">Step 2 Content</div>
    </ud-step>
    <ud-step title="Step 3">
      <div slot="content">Step 3 Content</div>
    </ud-step>
</ud-stepper>
```

## Install the Polymer-CLI

First, make sure you have the
[Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run
`polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via
[web-component-tester](https://github.com/Polymer/web-component-tester). Run
`polymer test` to run your application's test suite locally.
