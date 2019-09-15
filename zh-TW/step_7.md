## 閃亮之星

Now you will combine loops to make a shining star.

\--- task \--- Add a 'star' sprite to your stage.

![添加一個星星角色](images/space-star-sprite.png)

\--- /task \---

\--- task \--- Can you add code to your star sprite to make the star repeatedly grow and shrink?

![測試一顆閃亮的星星](images/sprite-star.png)

\--- hints \--- \--- hint \--- 當 **綠旗**被點擊時，你的星星角色應該會 **改變尺寸** 變大幾次，然後再**改變尺寸** 變小幾次。 It should do this so that it gets bigger and then smaller **forever** and looks like it's shining light. \--- /hint \--- \--- hint \--- Here are the code blocks you need:

```blocks3
repeat (10)
end

when flag clicked

repeat (10)
end

change size by (10)

change size by (10)

forever
```

\--- /hint \--- \--- hint \--- Here's the code to make your star grow and shrink: ![Star sprite](images/sprite-star.png)

```blocks3
when flag clicked
forever
    repeat (20)
        change size by (2)
    end
    repeat (20)
        change size by (-2)
    end

```

\--- /hint \--- \--- /hints \--- \--- /task \---