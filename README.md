# &#60;dsc-polymer-form-contact&#62;

![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-form-contact.svg?branch=master)
![Bower version](https://img.shields.io/bower/v/dsc-polymer-form-contact.svg)
![](https://img.shields.io/pypi/l/Django.svg)

Basic and standard form component with Polymer. This project use Google Material Design.

![demo](https://raw.githubusercontent.com/discovery-tecnologia/dsc-polymer-form-contact/master/docs/img/form.png)

## Demo

```
$ git clone https://github.com/discovery-tecnologia/dsc-polymer-form-contact.git
$ cd dsc-polymer-form-contact
$ npm install
$ npm install -g polymer-cli
$ polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-form-contact/demo/index.html

## Usage

Install with:

```
$ bower i dsc-polymer-form-contact --save
```

Example usage:

```html
<dsc-polymer-form-contact language="br" endpoint="http://my-site/my-api"></dsc-polymer-form-contact>
```

## API

| Property       | Description                            | Default                           |
|:---------------|----------------------------------------|-----------------------------------|
| language       | Translate the form messages and labels | en                                |
| endpoint       | Endpoint API                           | http://localhost:3000/api/contact |

The file [locales.json](https://github.com/discovery-tecnologia/dsc-polymer-form-contact/blob/master/locales.json) contains the map of languages translated (EN,BR,ES).

## Test

Check sintax and execute selenium tests.

```
$ npm test
```

## TODO

 * more tests
