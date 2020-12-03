## The cascade is the name for this set of rules. It determines how conflicts are resolved, and it’s a fundamental part of how the language works. Although most expe- rienced developers have a general sense of the cascade, parts of it are sometimes misunderstood.

## Let’s unpack the cascade. When declarations conflict, the cascade considers three things to resolve the difference:

- Stylesheet origin—Where the styles come from. Your styles are applied in conjunc- tion with the browser’s default styles.
- Selector specificity—Which selectors take precedence over which.
- Source order—Order in which styles are declared in the stylesheet.
