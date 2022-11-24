# argoCD Blue/Green

- 무중단배포 Blue/Green 테스트용

## command
- rollout list 확인
```
kubectl argo rollouts list rollout -n 'namespace'
```

- blue(active) -> green(preview) 교체
```
 kubectl argo rollouts promote -n 'namespace' 'spec.selector.app'
```

## 확인

## References

- 
