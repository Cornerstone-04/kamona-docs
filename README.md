<div align="center">
    <img src="./assets/logo-primary-lg.svg" alt="Moniepoint primary Logo">
    <h1>Kamona UI</h1>
</div>

> Kamona is a design system created to be a platform-agnostic and consistent experience. Read more [here](https://moniepoint.com/blog/meet-kamona-the-design-system-pulsing-through-teamapts-products).

## Resources and Links

1. [`Figma`]() - Design Specifications
2. [`Jira`](https://teamapt.atlassian.net/jira/software/projects/KAM/boards/266) - Task Management and issue tracking

## Development & Usage

### Requirements

1. [`NodeJS`](https://nodejs.org)
2. [`Pnpm`](https://pnpm.io)

### Installation

- Clone the repo locally

```bash
git clone https://gitlab.com/tcosmos/kamona-ui/kamona-ui-lib.git
cd kamona-ui-lib
pnpm install
pnpm run storybook-v2:preview
```

- Open your browser and visit **http://localhost:4400**.

### Contributing

> Before contributing, take a look at the [Contributing Guidelines](https://teamapt.atlassian.net/wiki/spaces/MAE/pages/1272709130/Contribution+Guidelines).

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

To only run on affected or changed code, use:

```bash
pnpm lint
```

Check for linting errors with:

```bash
pnpm lint:all
```

To fix all fixable errors, use:

```bash
pnpm lint:fix
```

To fix all fixable errors, use:

```bash
pnpm lint:fix_all
```

### Building Project

For building only affected changes, run:

```bash
pnpm build
```

To build all projects with a build target, run:

```bash
pnpm build:all
```

### Folder Structure

- `.nx` -
  - `cache`
- `.vscode`
- `apps`
  - `kamona_stories`
    - `.storybook`
    - `public`
    - `src`
      - `resources`
  - `v2`
- `ci`
  - `kubernetes`
    - `development`
      - `charts`
        - `templates`
  - `v2`
    - `kubernetes`
      - `development`
        - `charts`
          - `templates`
- `lib`
  - `core`
  - `icons`
    - `icons`
    - `scripts`
    - `src`
    - `twotone-icons`
  - `utils`
    - `src`
      - `events`
      - `flags`
      - `form`
      - `internationalization`
      - `moment`
      - `save-file`
      - `screen`
      - `scripts`
        - `internationalizsation`
      - `shared`
      - `storagetypes`
  - `v2`
    - `components`
    - `icons`
    - `styled-systems`
    - `tailwind-plugins`
    - `tokens`
    - `utils`
- `patches`
