Minimisation is highly important in machine learning. The cost function measures how well our model's predictions match the actual data. Through minimisation we can better align our model with its target. In this section we'll cover some methods of approaching minimisation. 

## Newton's Method
This method relies on your [differentiation](Differentiation) skills, if you're a bit rusty make sure to take a refresher then come back! 
Newton's Method hunts for the roots of a given equation. The roots are the values that make that function equivalent to 0.  


<iframe width="560" height="315"
  src="https://www.youtube.com/embed/-5e2cULI3H8"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

Note: Newton's Method is fast but it requires the derivative of the function to be taken and also is not guaranteed to find a root.

## Bisection
Bisection (Intermediate Value Theorem) is a simpler and less efficient approach than Newton's Method. The difference being that once its conditions are met, Bisection is guaranteed to find a root.

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/OzFuihxtbtA"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>