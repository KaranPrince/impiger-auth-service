# Troubleshooting

## Pod CrashLoopBackOff

Check:

kubectl logs <pod-name>

## Deployment Status

kubectl rollout status deployment/impiger-auth-service -n impiger-platform
