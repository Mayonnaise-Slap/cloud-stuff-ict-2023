# Команда Облаке

**Вариант 11**

## Задача

> Возьмите по 1 публичному облачному провайдеру в РФ и за рубежом (напр. VK Cloud и AWS). Сравните российских и зарубежных облачных провайдеров по каждому из IT Towers (сервисы в Compute, Storage, Networking, Cloud Services, etc…). Покажите, какие задачи лучше решаются российскими провайдерами. По возможности, не повторяйтесь с выбором сравнивая в рамках команды, напр. один человек сравнивает VK и AWS, другой VK и Yandex.Cloud, третий Azure и VK.

## Решение

### Сравнение Яндекс.Облака с Azure и AWS

| Azure              | AWS                                    | Яндекс.Облако                                   |
| ------------------ | -------------------------------------- | ----------------------------------------------- |
| Data Lake Store    | S3 + Athena                            | Object Storage + Managed Service for PostgreSQL |
| SQL Data Warehouse | Redshift                               | Managed Service for PostgreSQL                  |
| Functions          | Lambda                                 | Functions                                       |
| Traffic Manager    | Route 53                               | DNS                                             |
| Azure Firewall     | VPC + Security Groups                  | Virtual Private Cloud + Security groups         |
| Notification Hubs  | SNS                                    | Pub/Sub                                         |
| Power BI           | QuickSight                             | Managed Service for ClickHouse                  |
| Recovery Services  | Backup + CloudEndure Disaster Recovery | Backup + Восстановление ВМ                      |
| Scheduler          | CloudWatch Events                      | Scheduler                                       |
| Sentinel           | GuardDuty                              | K8S Security                                    |
| SQL Database       | RDS                                    | Managed Service for PostgreSQL                  |

## Преимущества Яндекс.Облака перед Azure и AWS

- Яндекс.Облако предоставляет высокопроизводительные управляемые сервисы для PostgreSQL и ClickHouse, обеспечивая простоту в использовании, автоматическую масштабируемость и поддержку баз данных.
- Яндекс.Облако имеет интеграцию с Kubernetes, что обеспечивает удобство в управлении контейнерами. Это может быть привлекательным для команд, использующих Kubernetes для оркестрации и управления контейнеризированными приложениями.
- Яндекс.Облако предоставляет гибкие средства управления безопасностью, включая Virtual Private Cloud и Security Groups.
- Яндекс.Облако предоставляет сервисы (Managed Service for AI) для искусственного интеллекта, что может быть привлекательным для проектов, требующих анализа данных, машинного обучения и других возможностей искусственного интеллекта.

Все эти технологические решения позволяют разработчикам эффективно строить и масштабировать свои проекты в облаке, обеспечивая высокую производительность и безопасность.
