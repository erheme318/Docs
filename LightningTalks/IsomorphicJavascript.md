Presenter: Kim

### Isomorphisme (javascript)

df:
 Share same template in server rendering javascript and client rendering javascript.

Javascript rendering
 - Fetch html from server
 - Fetch javascripts from server
 - Process html rendering via javascript execution

Note:
 - Google analytics don't support client side rendering because there's no html
   when a bot visits the site without javascript enabled.


Structure:

                              API
                 ______________|______________
                |                            |
         Node server (client1) <-------> Browser (Client2)
      


ReactDOM rendering logic:
 - Check Dom collection in memory (virtual DOM)
 - Manipulate difference between in-memory with actualy dom



Further reading:
 - React DOM rendering logic (rendering optimization)
 - Advantages of React over other alternatives


Questions:
 - Does the client (browser) need to call to real API instead of passing by Node server ?
 - Is it possible to use node server as server balancer ?
