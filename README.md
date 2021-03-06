# Hodor: Distributed AI Helper with RDF.

*read in other language: [简体中文](zh/README.md)*

## Table of Contents

- [Overview](#Overview)
  - [Introduction](#introduction)
  - [Project structure](#project-structure)
- [Project Design](#project-design)
  - [Paper and Documents](#paper-and-documents)
- [State of project](#state-of-project)
  - [Implementation](#Implementation)
- [License](#License)

## Overview

### Introduction

![](img/hodor.jpg)

### Project structure

This part present all project structure and this project's location.

- [Yinet](https://github.com/Yinet-project/Yinet): Root project.
  
  - [Stem](https://github.com/Yinet-project/Stem): A distributed infrastructure.
  - [Lightcore](https://github.com/Yinet-project/Lightcore): A lightweight flexable blockchain framework.
  - [Hodor](https://github.com/Yinet-project/Hodor): Distributed AI Helper with RDF.
  - [Karma](https://github.com/Yinet-project/Karma): Advance cryptography toolkits.
  - [Vida](https://github.com/Yinet-project/Stem): Misc project of `Yinet` for application.
  - [Curdata](): Application at financial.
  
  ## Project Design

To learn more design detail for this project, please read [Paper and Documents](#Paper and Documents). 

### Paper and Documents

- [Whitepaper](en/whitepaper.md): Describe `Hodor`'s aims and design principle.
- [RFCs](en/rfcs/index.md): Describe the detail of project.

## State of project

***Stem is a work in process!***

### Implementation

- Rust
  - [triples-node](#): Triples storage and query for one node.
  - [dtriples](#): A distributed RDF Database.

We present project's roadmap here.

### Contribute

There are many way to contribute us. We welcome all type of contributions.

#### Help with the design

Please create issue for related project to discuss. Then you can propose a RFC to make these discuss to be a standard.

#### Help with the implementations

You can make issue and pull request for related implementation project.

## License

MIT
