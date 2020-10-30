# notes

For `<input type="text">` the event type is React.ChangeEvent<HTMLInputElement>
  
For `<textarea>` is React.ChangeEvent<HTMLTextAreaElement>
  
For `<select>` we use React.ChangeEvent<HTMLInputSelect>

[React Typescript cheatsheet: form elements and onChange event types](https://blaipratdesaba.com/react-typescript-cheatsheet-form-elements-and-onchange-event-types-8c2baf03230c)

---

const h1Ref = useRef`<HTMLHeadingElement>`(null);

const divRef = React.useRef`<HTMLDivElement>`(null);

const buttonRef = React.useRef`<HTMLButtonElement>`(null);

const brRef = React.useRef`<HTMLBRElement>`(null);

const linkRef = React.useRef`<HTMLLinkElement>`(null);
