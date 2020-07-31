# Movies Sample app

[![Develop on Okteto](https://okteto.com/develop-okteto.svg)](https://cloud.okteto.com/deploy?repository=https://github.com/okteto/movies)

[![Develop on Okteto](https://img.shields.io/badge/Okteto-Develop%20now!-00D1CA?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNCIgaGVpZ2h0PSIxNCIgdmlld0JveD0iMCAwIDE0IDE0Ij4KICA8cGF0aCBmaWxsPSIjMDBEMUNBIiBmaWxsLXJ1bGU9Im5vbnplcm8iIGQ9Ik0yLjkwNTUxIDEuMzY5NTZjMy4xNTAxLTIuMzA1MTMgNy41NzM3NC0xLjYyNjQ3IDkuOTg0MDIgMS40Nzk2LjQ2NDEuNTk4MDYuMzYzMTYgMS40OTAyNC0uMjg3OTcgMS44ODk5Mi0uNjUxMTMuMzk5NjctMS40ODgwNi4yODAwOS0xLjk0MjQzLS4zMDU0NC0xLjE2MDMzLTEuNDk1My0zLjEzNDgzLTIuMTA3MTEtNC45MzMzMS0xLjUxOTEtMS43OTczLjU4NzYtMi45ODYwMyAyLjI0MTM4LTIuOTQ2NTIgNC4xMDA2Ni4wMzk1NiAxLjg2MTI0IDEuMjE3NDIgMy41MDYxOCAzLjA0MjY3IDQuMDc2NTcgMS44MjMzNS41Njk3OSAzLjc1NDYtLjA0MTkgNC44NTIyMS0xLjU0ODYuNDg5NTctLjY3MjA0IDEuMjEyMTYtLjc5OSAxLjg5OTUzLS40MTEyLjY4NzM3LjM4NzgxLjc0NzMyIDEuMzY5NDkuMzIyMzUgMS45NzczNkMxMS41ODAyOCAxMi45MTU2IDkuNTM0ODQgMTMuOTg5MSA3LjI0NzI4IDE0Yy0yLjI4NjI2LjAxMDcyLTQuNDI5NC0xLjAxMzgzLTUuODE4NjYtMi44MDQ5NkMtLjk4MTY0IDguMDg4OTYtLjI0NDU4IDMuNjc0NyAyLjkwNTUxIDEuMzY5NTZ6bTkuMzExIDQuNTE2MmMuMzk1NzctLjE5MDY3Ljg2NTY2LS4xNTQwNCAxLjIzMjc1LjA5NTI2LjM2NjQ4LjI0ODg4LjU3NTU1LjY3MjM4LjU0ODM3IDEuMTExNzItLjAyNzI4LjQ0MDgtLjI4ODMuODMwNS0uNjg0NzUgMS4wMjE0OS0uMzk1NzcuMTkwNjctLjg2NTY2LjE1NDA0LTEuMjMyNzUtLjA5NTI2LS4zNjY0OC0uMjQ4ODgtLjU3NTU1LS42NzIzOS0uNTQ4MzctMS4xMTE3Mi4wMjcyOC0uNDQwODEuMjg4My0uODMwNS42ODQ3NS0xLjAyMTQ5eiIvPgo8L3N2Zz4K)](https://cloud.okteto.com/deploy)

This example shows how to leverage [Okteto](https://github.com/okteto/okteto) to develop a Node.js + React Sample App directly in Kubernetes. The Node + React Sample App is deployed using a [Helm Chart](https://github.com/okteto/movies/tree/master/chart). It creates the following components:

- A *React* based front-end, using [webpack](https://webpack.js.org) as bundler and *hot-reload server* for development.
- A very simple Node.js API using [Express](https://expressjs.com).
- A [MongoDB](https://www.mongodb.com) database.

This is the application used for the [How to Develop an Application based on Microservices](https://okteto.com/docs/tutorials/e2e) tutorial.
