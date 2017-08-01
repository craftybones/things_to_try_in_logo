# Things to try in Logo

Try the following things in Logo to better understand how things work. Take your time on each of these and understand what happens and why it happens.

<br>

What is returned? Will there be an error? Why? What kind?
```lisp
make "is_alive true
```
 <br>

Why does this work?
```lisp
make "is_alive "true
```
<br>

What does it return? If not, why does this fail?
```lisp
make "is_alive "true
(is_alive = true)
```
<br>


What does it return? If not, why does this fail?
```lisp
make "is_alive "true
(:is_alive = true)
```
<br>

What does it return? If not, why does this fail?
```lisp
make "is_alive "true
(:is_alive = :true)
```
<br>


Why is " different from : in the second line?
```lisp
make "is_alive "true
(:is_alive = "true)
```
<br>
