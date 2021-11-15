# docx-dev

![docx-dev icon](public/assets/favicon.ico)

View the output of your .docx LIVE in your browser while you are coding it using [docx.js](https://docx.js.org/).

[Getting started](#getting-started)

## Description

Working with [docx.js](https://github.com/dolanmiu/docx) can be painful without viewing the output of your code in
real-time. I created this project to help you work with [docx.js](https://docx.js.org/) in order to code word documents
easily. It offers a viewer for your .docx file, and a live preview of your code in real-time.

![how it works](https://user-images.githubusercontent.com/18899702/141786539-0149142b-1aa4-4af0-8f60-c373d07003d9.gif)

## Requirements

- Node.js v14.18.0 or higher

# Getting Started

1. Start by cloning the repository: `git clone git@github.com:naskio/docx-dev.git`
2. Install dependencies: `yarn install`
3. Run forward port script: `yarn forward_port`
4. Create `.env` file : `cp .env.example .env`
5. Add the url generated by `yarn forward_port` to your `.env` file (var `PUBLIC_URL`).
6. Run the server: `yarn start`
7. Open the Docx viewer at [`http://localhost:3000`](http://localhost:3000)
    - Start editing the document `./docx-src/source.js`
8. Save the file `./docx-src/source.js` and see the changes live in your browser.
    - You can find the generated document at `./docx-src/output.docx`

# Contributing

Don't hesitate to [open an issue](https://github.com/naskio/docx-dev/issues) or
to [submit a pull request](https://github.com/naskio/docx-dev/pulls) if you have any questions or suggestions.
