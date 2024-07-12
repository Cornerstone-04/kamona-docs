<div align="center">
    <img src="./assets/images/logo-primary-lg.svg" alt="Moniepoint primary Logo">
    <h1>Kamona UI</h1>
</div>

[![Moniepoint Cover Image](/assets/images/kamona-layout.png)](https://gitlab.com/tcosmos/kamona-ui/kamona-ui-lib)

## What is Kamona?

Kamona is a design system created to be a platform-agnostic and consistent experience.

## Features

- Brand identity/brand assets : visual design elements, typography, colours, etc.

- UI Library : interface elements and how they are styled.

- Codebase :  the code elements to be designed i.e. the code translation of the UI elements that have already been designed.

## Usage & Development

### Clone the repo locally

```bash
$ git clone https://gitlab.com/tcosmos/kamona-ui/kamona-ui-lib.git
$ cd kamona-ui-lib
$ pnpm install
$ pnpm run storybook-v2:preview
```

Open your browser and visit **_http://localhost:4400_**.

[![Moniepoint Cover Image](/assets/images/kamona-layout.png)](https://gitlab.com/tcosmos/kamona-ui/kamona-ui-lib)

### Usage

```tsx
export default () => (
  <>
    <Button appearance="danger" variant="ghost">
        Click Me
    </Button>
    <Alert
        action={{
            handler: () => {},
            label: 'Click Me'
        }}
        appearance="success"
        title="An Alert Title"
    />
  </>
);
```

## Contributing

We warmly invite contributions from everyone. Before you get started, please take a moment to review our [Contributing Guide](https://ant.design/docs/react/contributing). Feel free to share your ideas through [Pull Requests](https://github.com/ant-design/ant-design/pulls) or [GitHub Issues](https://github.com/ant-design/ant-design/issues). If you're interested in enhancing our codebase, explore the [Development Instructions](https://github.com/ant-design/ant-design/wiki/Development) and enjoy your coding journey! :)

For collaborators, adhere to our [Pull Request Principle](https://github.com/ant-design/ant-design/wiki/PR-principle) and utilize our [Pull Request Template](https://github.com/ant-design/ant-design/wiki/PR-principle#pull-request-template) when creating a Pull Request.
