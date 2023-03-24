# Routing looses focus in Norigin-Spatial.Navigation

See https://github.com/NoriginMedia/Norigin-Spatial-Navigation for libary documentation

When using the liberary together with react-router-dom, focus is lost, when there is many assets that are rendered.

Stepts to reproduce:
Set network and CPU to mid-tier mobile in chrome devtools

1. Click the second tab
2. Click the first tab
3. Go up. Focus is now lost

If enter is pressed, it is seen in the console that it is an element from /another, there is holding the focus.

The faster the steps are done, the more likely it is to loose focus.

## Setup

```sh
npm i
npm start
```
