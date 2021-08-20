# ![logo](assets/icon-32.png) Markdown in Outlook

![Release](https://github.com/chunliu/outlook-markdown/workflows/Release/badge.svg)

This is an add-in for Outlook which can help you edit the markdown, covert it to html and insert it to the email body.

## Install

1. Follow the instruction in [Sideload Outlook add-ins for testing](https://docs.microsoft.com/en-us/office/dev/add-ins/outlook/sideload-outlook-add-ins-for-testing) to install the add-in to Outlook.
1. In the **Custom add-ins** section, select **Add from URL** and input the URL of the manifest: `https://dmeatte-aq.github.io/outlook-markdown/dist/manifest.xml`.

## How to use

The add-in works for the compose scenario.

![How to use](olmd.gif)

## Libraries

The following libraries are used in the add-in.

- [showdown](https://github.com/showdownjs/showdown)
- [React Border Wrapper](https://github.com/Metroxe/react-border-wrapper)
