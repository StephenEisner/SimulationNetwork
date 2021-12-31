# ComputeNetwork
uses a network of gpus to do physics simulations which become nfts that look crazy. OPEN SOURCE!!!!

The network is built of nodes. Each node is a gpu(or cpu?) 

Value is based in rendering. Such that for each process your gpu is given to compute for a render you will be rewarded in token from the network.

A user would submit a file that needs to be rendered on a supported rendering framework(cycles for MVP). One benifit here is that because it is open source, users can work on their own supoort for a rendering protocol, and if approved and in the network can be used by anyone. Compared to rendercoin(only example out there) which is not open and there needs to be internal support for any redering system.

That file would then get its total cost estimation which would then be converted into the token value. (Need more work on that). Then utilizing as many gpus on the network as possible, the rendering would be dispatched to different gpus and collected back on the network which would then compile the render and send it back to the user in some smart contract where the network now has the payment. The network then redistributes the tokens to each of the gpus which did any rendering computation.

Compared to render token which is built for a privately owned cloud rendering platform, this network is built where any user can donate idle gpu will add to the growing network of gpus, meaning people with 1 gpu can earn from the same job as someone with 1000 gpus. 

        - Additionally we might want to figure out how the nodes connected will not waste energe when idle, i.e. a back up connection to a seperate mining platform like when ur not rendering you can choose to default to mine bitcoin or something idk.

Other goals for the project:
  - Building high level abstractions on the network so it can support other processes which could benifit from acess to multiple gpus i.e. machine learning
    - also cpu support
  - in other words we are building an economy upon decentralized and unspecified computation
