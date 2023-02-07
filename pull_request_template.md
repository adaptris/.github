## Motivation

Why am I doing this

## Modification

What did I change

## PR Checklist

- [x] been self-reviewed.
- [ ] Added javadocs for most classes and all non-trivial methods
- [ ] Added supporting annotations (like @XStreamAlias / @ComponentProfile)
- [ ] Added DefaultValue annotation when there is a default value (e.g. @DefaultValue('true'))
- [ ] Added validation annotation (@NotNull...) when required and add @Valid when nested class has some validation
- [ ] Checked that @NotNull and @NotBlank annotations have a meaningful message when appropriate.
- [ ] Checked that new 3rd party dependencies are appropriately licensed
- [ ] Added comments explaining the "why" and the intent of the code wherever it would not be obvious for an unfamiliar reader
- [ ] Added unit tests or modified existing tests to cover new code paths
- [ ] Tested new/updated components in the UI and at runtime in an Interlok instance
- [ ] Reviewed java class members so that missing annotations are added (InputFieldDefault/ComponentProfile etc)
- [ ] Checked that javadoc generation doesn't report errors
- [ ] Checked the display of the component in the UI
- [ ] Remove any config/license annotations
- [ ] Check the gradle build file to make sure the dependencies section is more explicit "implementation/api".

## Result

What's the end result for the user

## Testing

How can I test this if I'm reviewing this.
