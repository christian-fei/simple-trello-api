# simple-trello-api

super simple trello api for node.js

# supported endpoints

## getBoards

```js
  const boards = await getBoards({ key, token })
```

## getBoardLists

```js
  const lists = await getBoardLists({ key, token }, boardId)
```

## getBoardMembers

```js
  const members = await getBoardMembers({ key, token }, boardId)
```

## getBoardCards

```js
  const cards = await getBoardCards({ key, token }, boardId)
```