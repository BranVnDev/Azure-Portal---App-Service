# Azure Portal - App Service

Export de los recursos del grupo `rg-utvt-integradora-dev-mxc-001` (suscripción Azure for Students).

## Recursos

| Recurso | Tipo | Región |
|---|---|---|
| log-utvt-integradora-dev-mxc-001 | Log Analytics workspace | eastus2 |
| appi-utvt-integradora-dev-mxc-001 | Application Insights (workspace-based) | eastus2 |
| asp-utvt-integradora-dev-mxc-001 | App Service Plan Windows F1 | eastus2 |
| app-utvt-branvn-dev-mxc-001 | Web App Node 24 | eastus2 |

## Archivos

- `azuredeploy.json` — plantilla ARM exportada del grupo (read-only, para documentar).
- `params.md` — parámetros y tags usados.

## Tags comunes

cost_center=utv, environment=dev, managed_by=portal, owner=equipo-integradora

## Nota de regiones

La política `sys.regionrestriction` solo permite: northcentralus, centralus, westus3, eastus2, southcentralus. Por eso todo quedó en `eastus2` y no en Mexico Central.
