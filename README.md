# Lektor - static site builder with Python: how to use with Azure Static Web Apps

## What is lektor?

Static website generator Python library! See [a video demo (Korean) using lektor with comparison (PyCon Korea 2020)](https://youtu.be/PwEFsRIm3x4?t=711)

## How to build in your local environment

A yaml file in [.github/workflows directory](./.github/workflows) describes how to build
with Azure Static Web Apps in details. The following commands should be useful for your local build purpose:

```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -U wheel lektor
$ lektor plugins reinstall
$ lektor build --output-path site
```

## Related resources

- [Azure Static Web Apps - Product page](https://azure.microsoft.com/services/app-service/static/?ocid=AID3035096)
- [Docs: Azure Static Web Apps](https://docs.microsoft.com/azure/static-web-apps/?ocid=AID3035096)
- [Learn: Azure Static Web Apps](https://docs.microsoft.com/learn/paths/azure-static-web-apps/?ocid=AID3035096)

(This project was originally bootstrapped with "[lektor quickstart](https://www.getlektor.com/docs/quickstart/)" command and evolved from [a sample GitHub repository for my presentation at PyCon Korea 2020](https://github.com/ianychoi/lektor-pyconkr2020))
