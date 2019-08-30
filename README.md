# Mouse Control with Playing Cards

The whole point of the app is that you can control your PC/Laptop using webcam. I took cards, but it doesn't matter, it can be any darkish blue object in your hands. The most important thing is that your webcam should be enough qualitative to see the object. Now **where** can this technic be used? We can use it on various seminars to make the presentation more interesting, in 3D modeling to make it more natural and to feel the third dimension, in airports to automatize the airplane parking and etc.
And **how does this work**. OpenCV was used to create such an effect. It was said that only darkish blue colors should be selected and tracked. Then the centers of objects where found and bound to each other. And you should imagine that the middle of that binding is your mouse. But what if I say: *"Hey! But the middle of binding is inside the camera window! It cannot just work correct for the whole display"*. Don't worry! A bit geometry never hurts. We can use the ratio rules to make camera mouse display mouse. And it remains only to get used to that system. And we are done.
