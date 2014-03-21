# &lt;code-snippet&gt;

A web component for highlightjs implemented using Polymer.

After cloning this repository, run "bower install" to install Polymer and its
dependencies.

## Usage

1. Import Polymer:

    ```xml
    <script src="bower_components/polymer/polymer.js></script>
    ```

2. Import the custom element:

    ```xml
    <link rel="import" href="src/github-button.html">
    ```

3. Start using it!

    ```xml
    <code-snippet id="python-code" tabreplace="  ">...</code-snippet>
    ```

To view the demo, run an HTTP server:

    $ python -m SimpleHTTPServer 4444

Then visit http://localhost:4444/index.html in your browser.
