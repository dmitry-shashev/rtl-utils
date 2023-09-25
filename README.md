## Description

Utils for React Testing Library

## Install

For `npm`

```bash
npm install --save-dev rtl-utils
```

For `pnpm`

```bash
pnpm add -D rtl-utils
```

## API

```bash
textNotInTheDocument(text: string): Promise<void>
```

```bash
textInTheDocument(text: string | number): Promise<void>
```

```bash
ariaLabelInTheDocument(
  text: string,
  amount = 1
): Promise<void>
```

```bash
ariaLabelNotInTheDocument(text: string): Promise<void>
```

```bash
ariaLabelContainText(
  ariaLabel: string,
  text: string | number
): Promise<void>
```

```bash
ariaLabelNotContainText(
  ariaLabel: string,
  text: string | number
): Promise<void>
```

```bash
ariaLabelIsVisible(ariaLabel: string): Promise<void>
```

```bash
ariaLabelIsNotVisible(ariaLabel: string): Promise<void>
```

```bash
linkIsVisible(
  text: string,
  link: string,
  classNames: Array<string> = []
): Promise<void>
```

```bash
linkInTheDocument(
  ariaLabel: string,
  link: string,
  classNames: Array<string> = []
): Promise<void>
```

```bash
typeInInputByAriaLabel(
  ariaLabel: string,
  value: string
): Promise<void>
```

```bash
inputHasValue(
  ariaLabel: string,
  value: string
): Promise<void>
```

```bash
checkboxValueByTestId(
  testId: string,
  value: boolean
): Promise<void>
```

```bash
clickByAriaLabel(
  ariaLabel: string,
  position = 0
): Promise<void>
```

```bash
blurByAriaLabel(ariaLabel: string, position = 0): void
```

```bash
focusByAriaLabel(ariaLabel: string, position = 0): void
```

```bash
clickByRole(roleName: string, position = 0): Promise<void>
```

```bash
clickByTestId(testId: string): Promise<void>
```

```bash
clickByText(text: string): Promise<void>
```
