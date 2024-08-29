# Cody Custom Commands

## Inspiration

The inspiration behind this is purely out of laziness. I really don't want carpal tunnel syndrome when I'm older because I'm typing too much. But I LOVE creating programs!!!

That's why when AI Coding Assistant tools like [Cody](https://sourcegraph.com/cody) came out, I was excited to try them out.

With the ability to create custom commands, I thought it would be fun to create a set of commands that I could use to make my life easier.

In fact, I want to make every developer's life easier so that's why this is an open source project. Feel free to fork, clone, and contribute to this project.

As Jim Beach quoted Freddie Mercury: "You can do anything with my music. Just don't make it boring!"

All the best and happy coding!

![Freddie Mercury](./assets/freddie_mercury.jpeg)

## Prerequisites

1. Have [Cody extension](https://sourcegraph.com/cody) installed on VS Code
2. Have a Sourcegraph account

## How to use

### Step #1

Add the following NPM scripts to your `package.json` file:

```json
{
  "scripts": {
    "cody:get": "mkdir -p .vscode && curl -o .vscode/cody.json https://raw.githubusercontent.com/automation-consulting-2024/cody-custom-commands/main/cody.json",
    "predev": "npm run cody:get"
  }
}
```

### Step #2

There is no step #2.
