## org-labels-private

a Node.JS application to apply labels from the `style_guide` repo to all of the repos in the organization.

## Apply Labels JSON

`-d` destructive flag: delete any labels in a repo that are not currently in the JSON file

```
npm install
node bin/org-labels standardize -d 1T 1T/style_guide
```
