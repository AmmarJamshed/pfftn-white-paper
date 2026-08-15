# Publish on GitBook

## 1. Create / open a GitBook space

1. Go to [https://app.gitbook.com](https://app.gitbook.com)
2. Create a new space (or site section), e.g. **PFFTN White Paper**

## 2. Enable GitHub Sync

1. In the space header, click **Configure** / **Set up Git Sync**
2. Choose **GitHub**
3. Install the [GitBook GitHub App](https://github.com/apps/gitbook-com) if prompted
4. Select repository: **AmmarJamshed/pfftn-white-paper**
5. Branch: **main**
6. Initial sync direction: **GitHub → GitBook**
7. Content root: repository root (`.gitbook.yaml` is already configured)

## 3. Publish the site

1. Open your GitBook **site**
2. Click **Publish**
3. Share the public URL

## Notes

* Keep editing either in GitHub (Markdown) or via GitBook change requests after sync.
* Do not create a competing README page only inside GitBook UI while Git Sync is on — manage `README.md` in Git.
