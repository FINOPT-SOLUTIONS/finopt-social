# finopt-social

Approved social-media media for **Finopt** (@finopt.solutions): images and videos only.

These files are public on purpose: the scheduler (Metricool) fetches each post's media from its raw GitHub URL.

## Layout

```
brand/                      Profile picture, highlight covers and other brand assets
campaigns/YYYY-MM-wkN/
  postNN/                   One folder per post; carousel slides are numbered _s1, _s2, ...
```

Media URL pattern:

```
https://raw.githubusercontent.com/FINOPT-SOLUTIONS/finopt-social/main/campaigns/<week>/<post>/<file>
```

## Rules

- Only creatives that are ready for, or already in, publication.
- Never add credentials, customer data, private documents or unpublished strategy.
- Do not rename or move files that are already scheduled; their URLs must stay stable.
