Containo
===========================
[![Build Status](https://travis-ci.com/tomkerkhove/containo.svg?token=GsSXSXe5xF8ZdYK5qExq&branch=master)](https://travis-ci.com/tomkerkhove/containo)

Containo is a fictious company that is building a product that provides a catalog of products to buy that 3rd parties can consume.

The company is running their platform on Docker containers written in .NET Core. All of their APIs are being exposed via Kong as an API gateway.

![.NET Core](./media/dotnet.png)![Docker](./media/docker-logo.png)![Kong](./media/kong-logo.png)![Kubernetes](./media/kubernetes-logo.png)![Azure Service Fabric Mesh](./media/service-fabric-mesh-logo.png)

## Scenario
Containo provides an e-commerce SaaS platform where vendors can signup to become a vendor to sell products from the marketplace.
Customers can sign up and order products from either Containo itself or one of their trusted vendors.

Before an order is confirmed, the platform will verify if enough items are available in their own inventory or order more items with their vendors.

![Business Case](./media/docs/business-case.png)

_Services with * are not implemented yet._

----------------------------

:rotating_light: This is under active development and is currently limited to making orders.

----------------------------

## Documentation
Here is some documentation on this reference implementation
- [Building Containo](./build/README.md)
- [Deploying Containo](./deploy/README.md)
- [Service Fabric Mesh Composition](./docs/service-fabric-mesh-composition.md)
- [Kubernetes Composition](./docs/kubernetes-composition.md)

