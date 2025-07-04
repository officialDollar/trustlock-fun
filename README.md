# trustlock-fun
git checkout -b docs-dev-fix
git add .
git commit -m "add /docs/dev page"
git push origin docs-dev-fix
npx vercel --prebuilt
