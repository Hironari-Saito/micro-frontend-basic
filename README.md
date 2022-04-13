## Microfrontends with React: A Complete Developer's Guide
Udemyでのマイクロフロントエンドのコース用のレポジトリ

1. Designate one app as the Host and one as the Remote
2. In the Remote, decide which modules (files) you want to make available to other projects
3. Set up Module Federation plugin to expose those files
4. In the Host, decide which files you want to get from the remote
5. Set up Module Federation plugin to fetch those files
6. In the Host, refactor the entry point to load asynchronously
7. In the Host, import whatever files you need from the remote