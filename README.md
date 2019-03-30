1) mkdir eth-todo-list
2) cd eth-todo-list
3) truffle.init
4) touch package.json
5) npm install
7) write your contracts and migrations
8) deploy migration: $truffle migrate
9) open truffle console and do some testing stuff by running command: $truffle console
/*********   TRUFFLE CONSOLE START    *********/
  (i)   todoList = await TodoList.deployed()
  (ii)  todoList.address
  (iii) taskCount = await todoList.taskCount()
  (iv)  taskCount.toNumber()
/*********   TRUFFLE CONSOLE END    *********/