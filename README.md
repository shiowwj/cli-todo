# cli-todo

https://i.giphy.com/media/26ufnwz3wDUli7GU0/giphy.webp

Create a commandline todo list app that you can use from your terminal and that will keep track of things you need to do.

### Deliverables:

#### See the list

```
node todo.js show
```

```
1. [ ] - go shopping
2. [ ] - feed dog
3. [ ] - swim practice
4. [ ] - code app
5. [ ] - meet gabriel
```

#### Add to the list

```
node todo.js add "eat bak kut teh"
```

```
1. [ ] - go shopping
2. [ ] - feed dog
3. [ ] - swim practice
4. [ ] - code app
5. [ ] - meet gabriel
6. [ ] - eat bak kut teh
```

#### Further:

#### Mark as done

```
node todo.js done 4
```

```
1. [ ] - go shopping
2. [ ] - feed dog
3. [ ] - swim practice
4. [x] - code app
5. [ ] - meet gabriel
6. [ ] - eat bak kut teh
```

#### Further:
Add a column named `created_at` with data type date and display the date the item was added.

#### Further:
Add the ability to permanently delete an item.

#### Further:
Add a column named `updated_at` with data type date and display the date the item was marked completed.

#### Further:
Use an ascii art generator to add style to your app: [http://patorjk.com/software/taag](http://patorjk.com/software/taag) - here you could use the ES6 string interpolation syntax.

#### Further:
There are frameworks to make a completely dynamic command line app. Use a framework to make the app interactive: [https://medium.freecodecamp.org/writing-command-line-applications-in-nodejs-2cf8327eee2](https://medium.freecodecamp.org/writing-command-line-applications-in-nodejs-2cf8327eee2)