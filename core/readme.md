# OpenStack Core

All OpenStack files are written in JSON. They follow a fairly loose format, but whenever properties are marked as `required`, they are needed. And, if properties are marked as `optional`, they may be included, but it is not neccessary.

In the following documentation, there will be examples, notes, and schemas so you can have a better understanding of the OpenStack format.

## OpenStack - `required`

Without an OpenStack version number, the file will be disregarded. This is the most important property because it details how the following file will be parsed. This should be the first parameter, but as the files are stored as JSON, the order is irrelevant.

## Info - `required`

## Assets - `optional`

## Services - `optional`
