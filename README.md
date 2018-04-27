## org-labels-private

a Node.JS application to apply labels from the `style_guide` repo to all of the repos in the organization.

## Apply Labels JSON

`-d` destructive flag: if there are any labels in the repo not in the JSON file, they will be removed

```
npm install
node bin/org-labels standardize -d 1T 1T/style_guide
```
