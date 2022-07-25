# Running StarkNet Nodes (very easy) v2

*With the release of Pathfinder 0.2.6-alpha, you do no longer need any additional plugins to build the docker image. The JSON-RPC forwarding works now too! I can only recommend using docker instead of building the node from source!*

*For background on StarkNet and Pathfinder check my original post: https://medium.com/coinmonks/how-to-run-a-starknet-node-very-easy-7937e3a7d942.*

### The Super Easy Setup
*Using Pathfinder and Watchtower to set up a self-updating StarkNet node.*

1. Clone my docker-compose file
    ```
    git clone https://github.com/0xytoken/pathfinder-docker.git
    ```
2. Enter the repo and call docker-compose up.
    ```
    cd pathfinder-docker && docker-compose up
    ```
3. If Pathfinder and Watchtower spin up beautifully, then stop them and run the command again but this time in detached mode (aka. background)
    ```
    docker-compose -d up
    ```
4. If your Instances’ ports are open, then you can now query the nodes’ status on port 9545 using the JSON-RPC endpoint.

Feel free to try it out yourself [here](https://playground.open-rpc.org/?uiSchema%5BappBar%5D%5Bui:splitView%5D=false&schemaUrl=https://raw.githubusercontent.com/starkware-libs/starknet-specs/master/api/starknet_api_openrpc.json&uiSchema%5BappBar%5D%5Bui:input%5D=false&uiSchema%5BappBar%5D%5Bui:darkMode%5D=true&uiSchema%5BappBar%5D%5Bui:examplesDropdown%5D=false).

#### *Et Voilà!* ✨ Welcome to the ZK revolution 🚀

Give yourself a good pat on the ol’ back-a-rooney! You are awesome! Be proud of yourself for supporting #decentralization and #accessibility!

👇 Share your success with us in the StarkNet discord channel #full-node-success 👇

https://discord.com/invite/Fx6zFE7n

