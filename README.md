# craft-moon

    Crescent Moon

# Install:

    $ npm install craft-moon

# Parameters:

**crescent:** To adjust radius of crescent of moon

**radius:** To adjust radius of moon

**height:** To adjust height of moon

## Example:

```html
<craft>
    <craft name="moon" module="craft-moon"/>
    <lineup axis="x" spacing="1">
    <moon></moon>
    <moon crescent="3.5" radius="4" height="0.5"></moon>
    <moon crescent="2" radius="2" height="1"></moon>
    <moon crescent="2" radius="1"></ moon>
    </lineup>
</craft>
```

![example](example.png)
