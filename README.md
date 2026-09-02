# Agent Sandbox on Alibaba Cloud ComputeNest

Deploy an E2B-compatible Agent Sandbox service on Alibaba Cloud Container Compute Service (ACS), a new Container Service for Kubernetes (ACK) cluster, or an existing ACK cluster.

- [中文部署指南](docs/index.md)
- [English deployment guide](docs/index-en.md)
- [Deploy in Alibaba Cloud China](https://computenest.console.aliyun.com/service/instance/create/cn-hangzhou?type=user&ServiceId=service-47d7c54c78604e0bbe79)
- [Deploy on Alibaba Cloud International](https://computenest.console.alibabacloud.com/service/instance/create/ap-southeast-1?type=user&ServiceId=service-7c3a2fa4dd3e46519c59)

## Preview the documentation locally

The documentation site uses [MkDocs](https://www.mkdocs.org/) and the Alibaba Cloud ComputeNest theme.

```bash
python3 -m pip install --upgrade mkdocs mkdocs-aliyun-computenest
mkdocs serve
```

Open <http://127.0.0.1:8000/>. MkDocs rebuilds the site when you edit a file under `docs/`.

## Contribute

1. Create a branch from `main`.
2. Update both `docs/index.md` and `docs/index-en.md` when product behavior changes.
3. Run `mkdocs build --strict`.
4. Open a pull request against `main`.

GitHub Actions publishes the site after the pull request is merged.
