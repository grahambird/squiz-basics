# Glossary

Turning Squiz speak into English.

## Asset
Any item in the system (content, users, folders, templates, images, you name it).

## Asset list
Equivalent to a database query and foreach loop rolled into one. Highly configurable but slow on large sets of assets.

## Backend
Not so user friendly administration interface.

## Content Container
The building block of Standard Page assets and Paint Layouts. They can contain one or more Containers. The Container can be a WYSIWYG area, a nested asset, an HTML block and more.

## Context
Alternative versions of the same asset. The system starts with one context. Additional contexts can be added to allow authors to publish in multiple languages, for example.

## Data record
An "empty" asset. It has some basic properties but needs a Metadata Schema applied to it to become something useful.

## Design File
The page template. Can be used to generate HTML pages but also any other text-based format. It can contain "includes" via nesting other assets.

## Design Customisation
A child of a Design file. Customisations allow developers to change aspects of the page template without having to create new files.

## Easy Edit Suite
See Edit+.

## Edit+
JavaScript-powered user friendly authoring environment.

## Metadata Schema
Think "custom fields". Metadata schemas are applied to assets to supplement their native fields.

## Nested assets
An asset embedded in another asset. This allows developers (in Paint Layouts and Design Files) and authors (in Standard Pages) to create complex combinations of asset assembly.

## Paint Layout
These are effectively "asset templates" but can also be used as MVC-like controllers to abstract away complexity into multiple files.

## Standard Page
The most common asset type. Used for webpages but has other uses such as includes for Design Files.

## Trigger
Very powerful and flexible event-based actions. Can be used to make changes to the current asset on save, for example.

## Workflow
The system includes a totally customisable content workflow feature with email notifications. Branching can be based on many things including asset metadata which makes it very powerful.
