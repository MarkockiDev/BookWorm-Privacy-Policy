# BookWorm — Privacy Policy site

A single, self-contained `index.html` privacy policy for the BookWorm iOS app, styled to the app's design system. No build step, no dependencies (fonts load from Google Fonts CDN).

## Publish on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch **`main`** and folder **`/docs`**, then **Save**.
5. After a minute the policy is live at:
   `https://<your-username>.github.io/<repo-name>/`

Paste that URL into **App Store Connect → App Privacy → Privacy Policy URL**.

## Editing

Everything is in `index.html`. Update the **Last updated** date in the hero and the footer whenever the policy changes.
