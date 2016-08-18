hubot-stache
================

Hubot plugin to add a moustache to the face of a photo.

Currently this hubot plugin only works with Slack. If you would like to help port it to other platforms, submit a [Pull Request](https://github.com/neufeldtech/hubot-stache/pulls/)

## Installation
**This hubot script requires version 4+ of the [hubot-slack](https://github.com/slackhq/hubot-slack) slack adapter package**

* Run the ```npm install``` command

```
npm install hubot-stache --save
```

* Add the following code in your external-scripts.json file.

```
["hubot-stache"]
```

## Usage

- Upload a photo to slack (at least 500px x 300px) that contains at least one face
- Add a comment to the photo upload ```@hubot stache me```
- Hubot will upload a moustachified version of the photo to Slack
