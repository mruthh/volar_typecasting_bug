Minimal repro for a syntax highlighting bug in the Volar (Vue Official) VSCode extension.

Using TypeScript to cast the type of a prop inside a dynamic prop binding causes the parser to fail and stop syntax highlighting.
When you wrap the typecast prop in parentheses (or curly braces if a function), syntax highlighting works correctly.


## Incorrect syntax highlighting
<img width="689" height="431" alt="VS code screen with broken syntax highlighting" src="https://github.com/user-attachments/assets/ae102f0f-483b-421a-ab3c-d415edc50117" />

## Correct syntax highlighting
<img width="649" height="390" alt="VS code screen with functional syntax highlighting" src="https://github.com/user-attachments/assets/69d3d5ca-b602-452b-8b69-19dcba4f7781" />
