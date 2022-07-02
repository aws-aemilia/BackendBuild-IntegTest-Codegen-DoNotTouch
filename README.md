# Backend Build Integration Test 

- Uses node v14
- Uses Amplify CLI 5.1.3
- Creates an AppSync API
- Used codegen to generate graphql statements and types

# Note

This repo is duplicated in 2 different branches: `mainline` and `pboundary`. This is because Amplify CLI uses the branch name to create the backend environment. So if multiple integration tests are using the same repo with the same branch, there are conflicts naming resources like S3 buckets. 
