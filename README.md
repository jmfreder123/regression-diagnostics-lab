# Regression Diagnostics Lab

An interactive, single-file teaching tool for regression diagnostics (leverage, studentized deleted residuals, DFFITS, DFBETAS) and multicollinearity (VIF, tolerance, inflated standard errors). It's self-contained, with no external libraries, so everything lives in `index.html`. All data are simulated.

## Publish on GitHub Pages

1. Create a public repo (for example, `regression-diagnostics-lab`) and add `index.html` to the root.
2. Go to the repo's **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
3. After a minute or two the site is live at `https://<your-username>.github.io/regression-diagnostics-lab/`.

## Embed in Canvas

On a Canvas page, open the HTML editor (`</>`) and paste:

```html
<iframe src="https://<your-username>.github.io/regression-diagnostics-lab/"
        width="100%" height="1500" style="border:0" title="Regression Diagnostics Lab"></iframe>
```

You can also link to the URL directly, which gives students the full browser width.

Notes:
- Challenge progress is saved in each student's own browser (localStorage). Nothing is sent to you or to Canvas, so the tool doesn't grade anything.
- Some Canvas iframe settings block file downloads. If the **Download CSV** button doesn't work inside the embed, it will work when the page is opened directly.
