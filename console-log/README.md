console-log
===========

Web-component for logging. It is especially useful to debug data binds. It supports both simple strings and complex JavaScript objects, which can be inspected in the console window.

## Demo

Please see the [demo page](https://nhnb.github.io/console-log/console-log/demo.html).


## Usage

Hello world:

    <console-log log="Hello World"> </console-log>

Complex objects:
    
    <template repeat="{{element in list}}">
        <console-log log="{{element}}"> </console-log>
    </template>

Log levels:

    <console-log log="log"></console-log>
    <console-log info="info"></console-log>
    <console-log warn="warn"></console-log>
    <console-log error="error"></console-log>
