## Kyverno Cleanup Policies

Kyverno policies that can scale down / report:

✅ Workbenches
✅ Pipelines (running pods that run too long) (and pipelines scheduled to run too often)
✅ InferenceServices for Model Serving
✅ Ray Clusters
✅ Deployments using GPUs (LLMs or similar)
- Any other resources that might have been created and results in a constantly running pod. Apps, microservices, databases, etc… 
- Cronjobs also need to be auto-turned off after a while. 

