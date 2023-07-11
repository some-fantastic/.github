# Some Fantastic

Home of silly demos with a purpose.

## Fizzbuzz

Not content with your standard whiteboard exercise of boring coding interviews, the three repositories demonstrate a "low-to-high" coding exercise where you have some teams who can work on parts of a project without seeing things on the high side.  Here's a high level:

- [lesser-fizzbuzz](https://github.com/some-fantastic/lesser-fizzbuzz) - most work happens here, in commercial clouds :heart:
- [greater-fizzbuzz](https://github.com/some-fantastic/greater-fizzbuzz) - not exactly a fork of :point_up:, but a copy maintained via patches sent over to the high side.
- [fizzbuzzbang](https://github.com/some-fantastic/fizzbuzzbang) - the finished product, assembled on the high side. :tada:

```mermaid
flowchart TD
    A(lesser-fizzbuzz\nfa:fa-cloud commercial cloud) -->|git patch on release| B{inspection\nfa:fa-shoe-prints sneakernet/diode}
    B --> |rejection| C(fa:fa-rectangle-xmark code rejected)
    C --> |human explanation\nof rejection\n-need to know-| A
    B --> |acceptance| D(greater-fizzbuzz\nfa:fa-shield-halved government cloud)
    D --> |git submodule of| E(fizzbuzzbang\nfa:fa-shield-halved government cloud)
```

Documentation you may find handy:

- [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- [git format patch](https://git-scm.com/docs/git-format-patch) and [git apply](https://git-scm.com/docs/git-apply) for using a [patch based workflow](https://nasamuffin.github.io/git/open-source/email/code-review/2019/05/22/how-i-learned-to-love-email-patches.html)

## Fedora ACS Override

This is a fork of [fedora-acs-override](https://github.com/some-natalie/fedora-acs-override) that adds some matrix builds and doesn't upload the finished product.  It's used for benchmarks and will be used for later cost analysis.  Some work posted [here](https://some-natalie.dev/blog/revisiting-build-times/) already.
