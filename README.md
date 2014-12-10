Sassdoc Bugs
============

Install Sassdoc
---------------

`npm install sassdoc -g`

Execute
-------

`sassdoc src/ dist/ --config=config.json --verbose`

Documented bugs
---------------

### See reference bug

~~`@see`reference can't be found.~~ - Seems to be fixed https://github.com/SassDoc/sassdoc/issues/291#issuecomment-66461440

-	Look at [src/see-reference-bug.scss](src/see-reference-bug.scss)
-	Issue: [https://github.com/SassDoc/sassdoc/issues/291](https://github.com/SassDoc/sassdoc/issues/291)

### Todo bug

`@todo` annotation not getting included in the rendered output.

-	Look at [src/todo-bug.scss](src/todo-bug.scss)
-	Issue: [https://github.com/SassDoc/sassdoc/issues/293](https://github.com/SassDoc/sassdoc/issues/293)

### Requires autofill bug

Autofill of `@requires` adds dependencies multiple times.

-	Look at [src/requires-autofill-bug.scss](src/requires-autofill-bug.scss)
-	Issue: [https://github.com/SassDoc/sassdoc/issues/293](https://github.com/SassDoc/sassdoc/issues/294)
