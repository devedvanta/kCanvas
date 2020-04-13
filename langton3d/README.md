# Langton's Ant in 3d

# Aim
This page would use a-frame to simulate a 2-D termite, in a 3D world.

To leverage the extra dimention we have, we keep on increasing the size of the block, if the termite revisits.

[Live Page](kCanvas/langton3d/kaaro.html)


## How to Run Custom Rules
To edit and run on a custom rule set, update `allTermites` array with custom rules, using a 'LangtonTermite' object.

```
LangtonTermite (
    start_x: starting x cordinate (required), 
    start_y: starting y cordinate (required),
    start_z: starting z cordinate (required),
    orientation: heading direction takes values 0 to 5 (defualt = 5),
    transition: array of 'L' and 'R' describing state table of the ANT (default = ['L', 'R']), 
    numberOfStates: the length of state table, just do it. (default=2)
)
```

And deploy.


#### How to deploy (using Github pages!)
##### Step 1:
Fork this repository.
##### Step 2:
Enable GitHub pages for you fork.
##### Step 3:
You are ready to use GitHub online editor make and commit changes.

The Langton's Ant UI should be live on ``` http://<your-username>.github.io/kCanvas/langton3d/index.html ```

## In-works


* additional `transition` *U* to run on z-axis.
* Sound! How does an Ant Sound-like. 