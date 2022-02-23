# Example

This folder contains different example for different cases. All example are nodejs script, so can be easily run by `node` command.

- pos - pos folder contains examples related to pos api

## How to use

### 1. Set configuration

You need to configure your environment variables now. Copy `.env.example` and rename as `.env`. Now provide values for the keys mentioned there.

There are some prefilled data in `config.js` but feel free to change anything as per your needs.

**Note:** - Be careful with your private key, Use a key you are comfortable with for development purpose. And try not to make it public by doing actions such as commiting to repo or referencing on any online site.

### 2. Install package

install related package by running command -

```
npm i
```

**Note:-** Make sure you are inside examples folder.

### 3. Run script

run any example script by using

```
node <file_path>
```

let's run a plasma erc20 balance example

```
node pos\erc20\deposit.js 
```
