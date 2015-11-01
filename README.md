Open Link plugin
==================================================

The **Open Link** is a very simple plugin, extending context menu with a possibility to open link in a new tab.

* extending context menu with a possibility to open link in a new tab,
* allwoing you to open link with a ctrl/cmd click,

It also integrates with linked [image2](http://ckeditor.com/addon/image2) widgets.

## Browser Compatibility

Basically the same as [CKEditor](http://docs.ckeditor.com/#!/guide/dev_browsers) with one exception: opening a link with ctrl click does not work in Internet Explorer / Edge browsers. Pull requests are welcome.

## Config Options

There are few config options available, you need to define them in standard [CKEditor config](http://docs.ckeditor.com/#!/guide/dev_configuration) object.

### `config.openlink_modifier`

Defaults to: `CKEDITOR.CTRL`

### `config.openlink_enableReadOnly`

Determines whether this plugin feature should be available also in read-only mode. For backawrd compatibility reason this value is set to `false` by default.

Defaults to: `false`

## Installation

See the official [Plugin Installation Guide](http://docs.ckeditor.com/#!/guide/dev_plugins).
