# input

Input styles and variables.

## Installation

```sh
$ npm install shoelace-ui-input
```

## Usage

Since most applications rarely if ever anything other than text inputs,
styles for these lesser-seen inputs are not included by default:

- password
- datetime
- datetime-local
- date
- month
- time
- week
- number
- email
- url
- search
- tel
- color

To apply the same input styles to these elements, assign `true` to the
proper variables before loading.

### Example

```stylus
input--apply-text     = true //- this is the only input by default
input--apply-password = true
input--apply-date     = true
```

Now your text, password, and date inputs all share the same styles.

## License

MIT
