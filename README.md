# Takeoff: Perplexity API

This module is a guide to the Perplexity API.

## Resources

- [Takeoff](https://JoinTakeoff.com)
- [Perplexity Docs](https://platform.perplexity.com/docs/overview)
- [Perplexity API Reference](https://platform.perplexity.com/docs/api-reference)

## Recommendations

We recommend using [Cursor](https://cursor.sh/) to write code.

## Prerequisites

You will need an Perplexity API Key.

Get one [here](https://platform.perplexity.com/api-keys).

Copy the `.env.example` file to `.env`.

```bash
cp .env.example .env
```

In `.env`, fill in the API key.

```bash
PERPLEXITY_API_KEY=your-perplexity-api-key
```

## Install Packages

```bash
npm i
```

## Structure

The example code is in the `examples` folder.

Your code is in the `me` folder.

## Run Code

Install `tsx` to run the examples.

```bash
npm i -g tsx
```

Example: Run the `audio-create-speech-example` and `audio-create-speech-me` files.

Copy the relative path of the file.

For the example code, run the following command:

```bash
tsx examples/audio/create-speech.ts
```

For your code, run the following command:

```bash
tsx me/audio/create-speech.ts
```
