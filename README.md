# FARTEX.SPACE

A responsive static parody landing page styled to match the supplied 1012×570 visual reference.

## Cloudflare Pages deployment
This is a static site. It does not need a Worker, server, build command, or framework.

### Direct upload
1. Extract `fartex-space.zip`.
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Upload assets.
3. Project name: `fartex-space`.
4. Upload the contents of this folder. `index.html` must be at the root.
5. Deploy and test the generated `*.pages.dev` URL.

### Git-based deployment
1. Push the contents of this folder to a GitHub repository.
2. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
3. Select the repository and production branch.
4. Framework preset: None. Build command: blank. Build output directory: `/` (or `.` if required).
5. Deploy.

### Attach FARTEX.SPACE
In the Pages project, open Custom domains → Set up a domain → enter `fartex.space`. Add `www.fartex.space` if desired. Follow Cloudflare's DNS instructions. For an apex domain, the domain must be active on Cloudflare with Cloudflare nameservers.

### Local preview
Run `python3 -m http.server 8080` from this folder and visit http://localhost:8080.

No backend or secrets are required. This is parody and is not affiliated with ARTEX.
