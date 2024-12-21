To build:
```
jekyll serve
```

To install:
```
bundle install
```

To release:
```
rm -rf ../frontend/public/help
cp -a _site !$
cd ../frontend
git commit -a -m 'released from help repo'
git push
```
