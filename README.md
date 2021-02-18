## What is this repository for?

This repository is supposed to maintain and distribute VSCode user snippets for "the popular open-source contract for web professionals by Stuff & Nonsense".

The contract version this repository supports is maintained by [tony-caffe][tony]:
https://gist.github.com/tony-caffe/7c5f706730caaed2265624b214ff6534

### what are VSCode snippets?

> Code snippets are templates that make it easier to enter repeating code patterns, such as loops or conditional-statements.
>
> In Visual Studio Code, snippets appear in IntelliSense (⌃Space (Windows, Linux Ctrl+Space)) mixed with other suggestions, as well as in a dedicated snippet picker (Insert Snippet in the Command Palette). There is also support for tab-completion: Enable it with "editor.tabCompletion": "on", type a snippet prefix (trigger text), and press Tab to insert a snippet.

[tony]: https://gist.github.com/tony-caffe

## Installation

- open VSCode;
- hit `F1`;
- type `>Preferences: Configure User Snippets` and hit `enter`;
- select the option to create "New Global Snippets file...";
- name the file whatever you want to;
- erase the contents of the newly created file;
- copy the contents of your desired `contract-killer.code-snippets` language;
- paste it inside of your newly created global snippets file.

## Usage

### method 1

- open a Markdown or plaintext file;
- hit `Ctrl + Space`;
- IntelliSense will pop up;
- select contract killer snippet;
- now, you just have to fill selected text placeholders, according to your needs;
- hit `Tab` every time you are done and want to go to the next placeholder.

### method 2

- open a Markdown or plaintext file;
- start typing "contract-killer";
- as soon as you type it, IntelliSense will suggest the snippet;
- select contract killer snippet;
- now, you just have to fill selected text placeholders, according to your needs;
- hit `Tab` every time you are done and want to go to the next placeholder.

## Translation

If you're newbie and don't know crap about Git and GitHub, feel free to [open an issue][new-issue] asking for help.

[new-issue]: https://github.com/riservato-xyz/contract-killer/issues/new

### from scratch

- fork this repository;
- clone to your computer;
- make a branch named with the **proper language and country code**;
  - `git checkout -b en_UK`
- make a folder named with the **proper language and country code**;
  - `mkdir en_UK`
- copy and paste files inside `en_US` to your folder;
- make an initial commit with this message:
  - `initial commit for en_UK`.
- start working on the translation, in the `contract-killer.code-snippets` file of your folder;
- push changes to your fork;
- make a pull request, from your newly created branch to our master one.

### continue the work of others

Please, read the ongoing translation file, before starting with your changes. This is going to help you have guidelines to what words to use.

- fork this repository;
- clone to your computer;
- make a branch named with the **proper language and country code**;
  - `git checkout -b en_UK`
- start working on the translation, in the `contract-killer.code-snippets` file of your desired language;
- push changes to your fork;
- make a pull request, from your newly created branch to our master one.
