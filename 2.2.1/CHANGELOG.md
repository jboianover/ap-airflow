# Changelog

Astronomer Certified 2.2.1-3, 2022-01-19
----------------------------------------
### Security

- Updated `celery` to `5.2.3` to fix [CVE-2021-23727](https://nvd.nist.gov/vuln/detail/CVE-2021-23727) ([commit](https://github.com/astronomer/ap-airflow/commit/b7ce051b726978691f6f37cb1f2f00a3c88da56f))
- Updated `Flask-AppBuilder` to `3.4.3` to fix [CVE-2021-41265](https://nvd.nist.gov/vuln/detail/CVE-2021-41265) ([commit](https://github.com/astronomer/ap-airflow/commit/b7ce051b726978691f6f37cb1f2f00a3c88da56f))
- Updated `numpy` to `1.21.5` to fix [CVE-2021-33430](https://nvd.nist.gov/vuln/detail/CVE-2021-33430) ([commit](https://github.com/astronomer/ap-airflow/commit/953ec71d9228f0c6558d4cd9aa74b8ddb5dfd141))

### Bugfixes

- Fix labels used to find queued KubeExecutor pods (#19904) ([commit](https://github.com/astronomer/airflow/commit/85cad14b556c57158ad533ddc8c74b6e2912c088))
- Update [Astronomer FAB Security Manager](https://github.com/astronomer/astronomer-fab-securitymanager) to version [1.8.1](https://github.com/astronomer/astronomer-fab-securitymanager/releases/tag/v1.8.1)

Astronomer Certified 2.2.1-2, 2021-11-05
----------------------------------------

### Bugfixes

- Only mark SchedulerJobs as failed, not any jobs (#19375) ([commit](https://github.com/astronomer/airflow/commit/fa0b99891f56b71466299aa4729c7193e609b263))

Astronomer Certified 2.2.1-1, 2021-11-02
----------------------------------------

User-facing CHANGELOG for AC 2.2.1+astro.1 from Airflow 2.2.1:

### Bugfixes

- Bugfix: Check next run exists before reading data interval (apache#19307) ([commit](https://github.com/astronomer/airflow/commit/0cca4bfb6922e54f940ae8e8fd415c9cf96e21ef))
- [astro] [AIRFLOW-5448] Handle istio-proxy for Kubernetes Pods ([commit](https://github.com/astronomer/airflow/commit/d56ba747a8b7263d0bfe83e3ac46b77a4ec0d113))
- [astro] Reconcile orphan holding table handling ([commit](https://github.com/astronomer/airflow/commit/98f53fa7ccf0c441b04e223d8ce6f4f365965eb9))
- [astro] Override UI with Astro theme, add AC version in footer ([commit](https://github.com/astronomer/airflow/commit/15c339b563e5d93e79c0bc4534c05e44aface42a))
