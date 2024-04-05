# tap-shopify-partner

`tap-shopify-partner` is a Singer tap for ShopifyPartner.


## Installation

```bash
pipx install tap-shopify-partner
```

## Configuration

### Accepted Config Options

- [ ] `Developer TODO:` Provide a list of config options accepted by the tap.

A full list of supported settings and capabilities for this
tap is available by running:

```bash
tap-shopify-partner --about
```

### Configure using environment variables

This Singer tap will automatically import any environment variables within the working directory's
`.env` if the `--config=ENV` is provided, such that config values will be considered if a matching
environment variable is set either in the terminal context or in the `.env` file.

### Source Authentication and Authorization


### Executing the Tap Directly

```bash
tap-shopify-partner --version
tap-shopify-partner --help
tap-shopify-partner --config CONFIG --discover > ./catalog.json
```

### Initialize your Development Environment

```bash
pipx install poetry
poetry install
```

### Create and Run Tests

Create tests within the `tap_shopify_partner/tests` subfolder and
  then run:

```bash
poetry run pytest
```

You can also test the `tap-shopify-partner` CLI interface directly using `poetry run`:

```bash
poetry run tap-shopify-partner --help
```
