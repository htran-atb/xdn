# xdn

A cheapo CDN.

- Files in github
- Delivered by jsDelivr
- Example: https://cdn.jsdelivr.net/gh/htran-atb/xdn@main/hello.js
- jsDelivr caches contents. Enter URLs [to purge cache](https://www.jsdelivr.com/tools/purge)



# Learned from

https://www.geeksforgeeks.org/git/hosting-your-scripts-from-github-to-jsdelivr-a-step-by-step-guide/


# To upload a new file
```
git clone https://pat-fg-1:$GITHUB_PASS@github.com/htran-atb/xdn.git
cd xdn
```
add a file, e.g. `hello.js`
git commit and push
File is ready at `https://cdn.jsdelivr.net/gh/htran-atb/xdn@main/hello.js`
You will get a cached version. Go [here](https://www.jsdelivr.com/tools/purge) to purge cache 