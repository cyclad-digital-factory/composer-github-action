# Composer github action

This action runs composer command on a PHP 7.2 env with several extensions already installed

## Inputs

### `composer-command`

**Required** The composer command to run. Default `"install"`.

## Example usage

```
uses: cyclad-digital-factory/composer-github-action@master
with:
  composer-command: 'install'
```