# AspNetCoreWebAPI
ASP.NET Web API for beginners 

CORS IN Web Api 
CORS -Cross-Origin Resource Sharing
1.when we need CORS policy? 
Ans: We need CORS policy when we want to share any resource from our domain to other domain,
when  we are sharing the resources within our same domain we don't need to define any policies 
=>CORS is a w3 standard that allows a server to relax the same origin policy that means when we are sharing the resources with in the same domain or same origins we don't need to check any policies so server will relax it will not check for any policies 


CORS SCENARIOS IN WEB Api
------there are three CORS scenarios
1.Simple requests.
2.Pre-flighted requests.
3.Request with Credentials.
----------------------------
 
there are three ways to enable CORS
1.In middleware using a named policy or default policy
2.Using endpoint routing.
3.With the [EnableCors] attribute.
