# &lt;vertical-progress&gt;

Fork of [&lt;paper-progress&gt;](https://github.com/PolymerElements/paper-progress) with a vertical layout.

Material design: [Progress & activity](https://www.google.com/design/spec/components/progress-activity.html)

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../paper-styles/color.html">
    <link rel="import" href="vertical-progress.html">
    <style is="custom-style">
      vertical-progress {
        display: block;
        width: 100%;
        margin: 20px 0;
      }
      vertical-progress.slow {
        --vertical-progress-indeterminate-cycle-duration: 5s;
      }
      vertical-progress.blue {
        --vertical-progress-active-color: var(--paper-light-blue-500);
        --vertical-progress-secondary-color: var(--paper-light-blue-100);
      }
      vertical-progress.red {
        --vertical-progress-active-color: var(--paper-red-500);
        --vertical-progress-secondary-color: var(--paper-red-100);
      }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<vertical-progress indeterminate class="blue"></vertical-progress>
<vertical-progress indeterminate class="slow red"></vertical-progress>
<vertical-progress value="40" secondary-progress="80"></vertical-progress>
```

The progress bars are for situations where the percentage completed can be
determined. They give users a quick sense of how much longer an operation
will take.

There is also a secondary progress which is useful for displaying intermediate
progress, such as the buffer level during a streaming playback progress bar.
