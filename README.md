inf-php
=======

Run a php interactive shell on emacs

usage
=====

put inf-php.el to load path, and add `(require 'inf-php)` to your .emacs.


In particular environments, php interactive shell may exit just after launching.
You can avoid this behaviour with `(setq inf-php-enable-launch-workaround t)`.
