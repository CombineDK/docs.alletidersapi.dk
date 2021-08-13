# docs.alletidersai.dk

Publib documentation for the GoTour API

## How to stuff

Just update the .md files in the project and push the changes. Github Pages takes care of the rest.

Convert the .apib files to html using Aglio:

```bash
docker run -ti --rm -v $PWD:/docs humangeo/aglio --theme-full-width -i ./provider-apiary.apib -o ./provider-apiary.html
docker run -ti --rm -v $PWD:/docs humangeo/aglio --theme-full-width -i ./sales-channel-apiary.apib -o ./sales-channel-apiary.html
```
