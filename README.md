# NgxCurrencyInputMask

This is an input mask implementation for Angular 2 and above.  It demonstrates how to use
[ControlValueAccessor](https://angular.io/api/forms/ControlValueAccessor) with an
attribute directive to mask text in an input field.  For this particular example the text
is masked to format the input display as decimals using the DecimalPipe but still maintain
a numeric/float value in the NgModel.

Here's the code running on stackblitz:

https://kkvijvmg.github.stackblitz.io

You can fork and make edits here:

https://stackblitz.com/github/tw3/ngx-currency-input-mask

Of course you can also clone this project and run or edit it locally as described below.

## Development server

Clone:

`git clone https://github.com/tw3/ngx-currency-input-mask.git`

Run `ng serve` for a dev server.

Navigate to `http://localhost:4200/`

The app will automatically reload if you change any of the source files.

## Related projects

* [Text Mask](https://github.com/text-mask/text-mask) (does not automatically unmask the value)
* [Autonumeric](https://github.com/autoNumeric/autoNumeric) (not angular-based)
* [Inputmask](https://github.com/RobinHerbots/Inputmask) (jQuery-based)

## Further help

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.5.

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

