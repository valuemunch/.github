<p align="center">
  <img src="https://avatars.githubusercontent.com/u/258364055?v=4" alt="ValueMunch" width="120">
</p>

# ValueMunch

**Trae Hackathon project for turning pantry ingredients into guided meal ideas.**

ValueMunch explores a mobile-friendly journey from a pantry photo to ingredient recognition, recipe suggestions, guided cooking, and a simple reward reveal. It is a hackathon prototype and project record, not an employer or operating company.

## Demo Walkthrough

1. Upload or capture a pantry or kitchen image.
2. Detect visible ingredients and generate three recipe suggestions.
3. Select a recipe and follow its cooking steps.
4. Complete the recipe to reveal the prototype reward experience.
5. Fall back to sample recipes when AI processing is unavailable.

## Prototype Architecture

```text
Progressive web application
        |
        +--> Image capture or upload
        +--> Gemini ingredient and recipe generation
        +--> Guided cooking state
        +--> Firebase-backed expanded demo features
```

## Public Repositories

| Repository | Purpose |
| --- | --- |
| [pantry-io](https://github.com/valuemunch/pantry-io) | Pantry-photo-to-recipe progressive web app prototype |
| [demo](https://github.com/valuemunch/demo) | Expanded React and Firebase meal-discovery experience |
| [plan](https://github.com/valuemunch/plan) | Product flow, architecture, API, error-handling, and UI planning documents |
| [hackathon](https://github.com/valuemunch/hackathon) | Initial Next.js hackathon scaffold retained as part of the build record |

## Scope

The reward is a deterministic demonstration rather than a live promotion or redemption system. Recipe and ingredient outputs should be reviewed by users and are not dietary or food-safety advice.

## Project Status

ValueMunch was built as a time-boxed hackathon collaboration. Contributors participated for the event; the organization does not represent an ongoing employment relationship.

[Open ValueMunch](https://valuemunch.web.app) | [Explore the repositories](https://github.com/orgs/valuemunch/repositories)
