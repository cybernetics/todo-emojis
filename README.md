# "To do" Emojis

## Abstract

This repo contains a set of "to do" emojis:

![live example](./docs/emojis.png)

You can use them in applications to create simple text-based to-do lists, **without plugins**:

![live example](./docs/example.png)

They were created by [Dave Stewart](https://twitter.com/dave_stewart) for use in the [Weekend Club](https://twitter.com/weekendclubldn) [Slack](https://slack.com) channel; an [Indie Hackers](https://indiehackers.com) in-person and virtual network based in London.

## Usage in Slack

### Installation

To get the emojis into Slack:

- download the [zip](https://github.com/davestewart/todo-emojis/releases/tag/v1.0.0) with the [png](./emojis/@4x) files
- follow the instructions to add emojis [here](https://slack.com/intl/en-gb/help/articles/206870177-Add-custom-emoji-to-your-workspace-Add-custom-emoji-to-your-workspace)

Use the high-res `@4x` versions to support high-DPI displays.

When you add the emojis, be sure to name them the same as the filenames, i.e.:

- `todo`
- `todo_doing`
- `todo_done`
- `todo_cancel`

### Create a to do list

Once added, just type `:todo` then choose the emoji from the list:

![emojis](./docs/edit-choose.png)

Then, add the text of the todo (and any other todo's, of course):

![todo](docs/edit-todo.png)

### Share progress

You can use the `todo_doing` emoji to indicate you've started a task:

![todo](docs/edit-doing.png)

When you've completed your task, edit the message and change the emoji to `todo_done`:

![todo](docs/edit-done.png)

If you want to let folks know you can't complete a task, use the `todo_cancel` emoji:

![todo](docs/edit-cancel.png)

It's the simplest way to share updates in Slack! 

## Artwork

If you want to modify the emojis, the original [Sketch](https://www.sketch.com/) file is in the [artwork](./artwork) folder.

## License

This work is licensed as [CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/deed.en).

