#Deployment plan
##Setting up the server
the server needs to be configured with the needs of very few users or 
data, as it is a single html page with no social or business
prominence.
##Git
Create new git branch if necessary

1. Checkout the branch you are working in
2. Develop
3. Git add
4. Commit with a message
5. Test branch
6. Merge to master branch
7. Review any changes to master branch
8. Push to staging server
9. Review on staging server
10. Promote to master branch of Production Server

If any problems arise, loop back to step 2

##Setting from git to server
For whatever reason, the server's git was set up wrong. So rather than 
fixing the problem, we're goin to work around it. Once finalized, any
changes are moved into the correct subdirectory and renamed if
necessary.



