# Medium Exporter
Export your stories published on medium.com to markdown.

![image](images/screenshot.png)

## Why?

I really enjoy using [Medium](https://medium.com) to publish articles related to programming, iOS and life. But I also want to have backup written in Markdown

## Contributions

I welcome contributions to make it work with other export formats. If you have any problem don't hesitate to open a new issue. If you have something to add or make the project better open a pull request!

## Installation

    npm install -g mediumexporter

## Usage

    $> mediumexporter https://medium.com/the-adventures-of-an-ios-developer/swift-guard-486f88ef5bd5 > medium_post.md

## Use it with Fish

    eval (mediumexporter https://medium.com/the-adventures-of-an-ios-developer/swift-guard-486f88ef5bd5 > medium_post.md)

To have a complete list of options:

    $> mediumexporter -h
