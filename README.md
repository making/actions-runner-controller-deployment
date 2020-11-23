```
ytt \
  -f vendor \
  -f config \
  -v github_token=${GITHUB_TOKEN} \
  | kubectl apply -f - 
```
