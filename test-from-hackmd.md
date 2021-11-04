# Test github

:::info
**Name:** `Pornrat`
**Student ID:** `123456`
:::

Pushed 04-Nov-21

## Question 1

Let $P$ be an image matrix of the letter `M`. 

```python
pts = [(0.,0.),(0.,3.),(1.,3.),(2.,2.),(3.,3.),(4.,3.),(4.,0.),(3.,0.),(3.,2.),(2.,1.),(1.,2.),(1.,0.),(0,0)]
P = matrix(pts).T
```

Rotate the image by the angle $\pi/7$ counter clockwise. Let $A$ be the image matrix that does this. Run the following code

```python
AP = A*P
print('The second point in AP is ',AP.columns()[1].n())
print('The sixth point in AP is ',AP.columns()[5].n())
pic = plotmat(AP)
txt = text('By ...',(2,0.5),background_color='orange') # modify text
show(pic+txt,gridlines=true,aspect_ratio=1,figsize=[4,4])
```

What results did you get?


## Question 2

Let $P$ be an image matrix of the letter `M`. 

```python
pts = [(0.,0.),(0.,3.),(1.,3.),(2.,2.),(3.,3.),(4.,3.),(4.,0.),(3.,0.),(3.,2.),(2.,1.),(1.,2.),(1.,0.),(0,0)]
P = matrix(pts).T
```

Translate the letter `M` so that its bottom right corner is at the position $(-4,4)$. Run the following codes.

```python
AP = A*P
print('The third column in A is ',A.columns()[2].n(2))
pic = plotmat(P,AP)
txt = text('By ...',(-4,2),background_color='orange') # modify text
show(pic+txt,gridlines=true,aspect_ratio=1,figsize=[8,4])
```

What results did you get?

## Question 3

Let $P$ be an image matrix of the letter `M`.

```python
pts = [(0.,0.),(0.,3.),(1.,3.),(2.,2.),(3.,3.),(4.,3.),(4.,0.),(3.,0.),(3.,2.),(2.,1.),(1.,2.),(1.,0.),(0,0)]
```

Find an affine matrix $A$ such that $AP$ gives the red `M` as in the following picture.

![](https://i.imgur.com/LjsAYby.png)

## Question 4


## Question 5

Let $P$ be an image matrix defined as follows. 

```python
pts = [(3,1),(2,6),(-1,4),(3,1)]
P = matrix(pts).T
```
Translate it by the vector $\begin{pmatrix}-3\\1\end{pmatrix}$. 
Find an affine matrix $A$ such that $AP$ gives the the resulting image. Plot the two images together. 


## Question 6

Let $P$ be an image matrix defined as follows. 

```python
pts = [(3,1),(2,6),(-1,4),(3,1)]
P = matrix(pts).T
```
Rotate it by the angle $\pi/3$ counter-clockwise around the point $(0,6)$. Find an affine matrix $A$ such that $AP$ gives the the resulting image. Plot the two images together. 


## Question 7

Let $P$ be an image matrix of a triangle defined as follows. 

```python
pts = [(5,3),(7,3),(6,5),(5,3)]
pts = homog(pts)
P = matrix(pts).T
```
Rotate the triangle by the angle $\pi/2$ counter-clockwise around the point $(2,3)$. Find an affine matrix $A$ such that $AP$ gives the the resulting image. Plot the two images together. 

Hello ajarn! this is a live document! 

Let $T:\mathbb{R}\longrightarrow \mathbb{R}$ be a linear transformation 
* A. yes
* B.
* C.
* D.



---



> I confirm that this is my work.
>  [name=Name, Student ID]