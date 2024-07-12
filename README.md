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

Read more [here](https://moniepoint.com/blog/meet-kamona-the-design-system-pulsing-through-teamapts-products).

## Development & Usage

### Clone the repo locally

```bash
$ git clone https://gitlab.com/tcosmos/kamona-ui/kamona-ui-lib.git
$ cd kamona-ui-lib
$ pnpm install
$ pnpm run storybook-v2:preview
```

Open your browser and visit **_http://localhost:4400_**.

![Kamona Storybook Preview](/assets/images/kamona-storybook.gif)

### Usage

```tsx
export const Component () => (
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

### Formatting

Check for linting errors with:

```bash
pnpm lint:all
```

To fix all fixable errors, use:

```bash
pnpm lint:fix_all
```

To only run on affected or changed code, use:

```bash
pnpm lint
```

To fix all fixable errors, use:

```bash
pnpm lint:fix
```

### Building Project

To build all projects with a build target, run:

```bash
pnpm build:all
```

For building only affected changes, run:

```bash
pnpm build
```

## Contributing

Before contributing, take a look at the [Contributing Guidelines](https://teamapt.atlassian.net/wiki/spaces/MAE/pages/1272709130/Contribution+Guidelines).
