# renovate-pr-test

This package adds `react-devtools-core` as a devDependency which has vulerability
in transitive dependency `shell-quote@1.7.2`.

From [renovatebot/renovate#16435](https://github.com/renovatebot/renovate/discussions/16435#discussioncomment-3175814)

> renovate can only open security PR for transitive dependencies in npm lockfile from npm version<7.
>
> you need to use lockfile maintenance for other lockfile versions.
