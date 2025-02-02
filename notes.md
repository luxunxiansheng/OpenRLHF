# Notes on git management
1. The orign's main branch is used as the base branch which will be synced with the forked repository main branch.
2. A devcontainer is added into the orign's main branch
3. Normally, we won't update the origin's main branch.
4. We only update the dev_in_container branch with our work. 
5. If the forked repository's main branch is updated, we will sync the forked repository's main branch with the origin's main branch.
6. And then merge the origin's main branch into the dev_in_container branch.