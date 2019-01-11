[fastify-oas](../README.md) > [fastifyOAS](../modules/fastifyoas.md) > [OpenApiSpec](../interfaces/fastifyoas.openapispec.md)

# Interface: OpenApiSpec

## Hierarchy

**OpenApiSpec**

## Index

### Properties

* [basePath](fastifyoas.openapispec.md#basepath)
* [components](fastifyoas.openapispec.md#components)
* [consumes](fastifyoas.openapispec.md#consumes)
* [externalDocs](fastifyoas.openapispec.md#externaldocs)
* [host](fastifyoas.openapispec.md#host)
* [info](fastifyoas.openapispec.md#info)
* [produces](fastifyoas.openapispec.md#produces)
* [schemes](fastifyoas.openapispec.md#schemes)
* [security](fastifyoas.openapispec.md#security)
* [securityDefinitions](fastifyoas.openapispec.md#securitydefinitions)
* [servers](fastifyoas.openapispec.md#servers)
* [tags](fastifyoas.openapispec.md#tags)
* [x-tagGroups](fastifyoas.openapispec.md#x_taggroups)

---

## Properties

<a id="basepath"></a>

### `<Optional>` basePath

**● basePath**: *`String`*

*Defined in [lib/index.d.ts:67](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L67)*

___
<a id="components"></a>

### `<Optional>` components

**● components**: *[ComponentsObject](componentsobject.md)*

*Defined in [lib/index.d.ts:76](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L76)*

___
<a id="consumes"></a>

### `<Optional>` consumes

**● consumes**: *`Array`<`String`>*

*Defined in [lib/index.d.ts:70](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L70)*

___
<a id="externaldocs"></a>

### `<Optional>` externalDocs

**● externalDocs**: *[ExternalDocumentationObject](externaldocumentationobject.md) | [ExternalDocs](externaldocs.md)*

*Defined in [lib/index.d.ts:65](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L65)*

___
<a id="host"></a>

### `<Optional>` host

**● host**: *`String`*

*Defined in [lib/index.d.ts:66](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L66)*

___
<a id="info"></a>

### `<Optional>` info

**● info**: *[InfoObject](infoobject.md) | [Info](info.md)*

*Defined in [lib/index.d.ts:64](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L64)*

___
<a id="produces"></a>

### `<Optional>` produces

**● produces**: *`Array`<`String`>*

*Defined in [lib/index.d.ts:71](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L71)*

___
<a id="schemes"></a>

### `<Optional>` schemes

**● schemes**: *[SchemasObject](schemasobject.md) | `Array`<`String`>*

*Defined in [lib/index.d.ts:69](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L69)*

___
<a id="security"></a>

### `<Optional>` security

**● security**: *`Array`<[SecurityRequirementObject](securityrequirementobject.md)> | `Array`<`object`>*

*Defined in [lib/index.d.ts:72](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L72)*

___
<a id="securitydefinitions"></a>

### `<Optional>` securityDefinitions

**● securityDefinitions**: *`object`*

*Defined in [lib/index.d.ts:77](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L77)*

#### Type declaration

[securityDefinitionName: `string`]: [Security](../#security)

___
<a id="servers"></a>

### `<Optional>` servers

**● servers**: *`Array`<[Server](../classes/server.md)>*

*Defined in [lib/index.d.ts:75](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L75)*

___
<a id="tags"></a>

### `<Optional>` tags

**● tags**: *`Array`<[TagObject](tagobject.md)> | `Array`<[Tag](tag.md)>*

*Defined in [lib/index.d.ts:80](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L80)*

___
<a id="x_taggroups"></a>

### `<Optional>` x-tagGroups

**● x-tagGroups**: *`String`*

*Defined in [lib/index.d.ts:68](https://github.com/Touffy/fastify-oas/blob/49c3b81/lib/index.d.ts#L68)*

___

