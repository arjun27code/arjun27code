# Setup

1. Copy every file in this pack into the root of:
   `arjun27code/arjun27code`

2. Commit and push:

```powershell
git add .
git commit -m "Install final GitHub profile"
git push origin main
```

3. Open the repository's Actions settings:

```powershell
Start-Process "https://github.com/arjun27code/arjun27code/settings/actions"
```

Under **Workflow permissions**, select **Read and write permissions**, then click **Save**.

4. Open Actions:

```powershell
Start-Process "https://github.com/arjun27code/arjun27code/actions"
```

Run **Generate Snake Animation** manually once.

5. Confirm that the output branch exists:

```powershell
git ls-remote --heads origin output
```

## Notes

- `dark.svg` and `light.svg` are real SVG code, not screenshots.
- The portrait is generated from Arjun's original photograph and embedded as vector paths.
- The visual sequence shows the portrait, n8n, Supabase and Security phases.
- The public GitHub stats endpoint can occasionally hit a rate limit. Self-host it later on Vercel for reliability.
- GitHub may cache raw SVG files. Add `?v=999` to a raw URL while testing a fresh version.
