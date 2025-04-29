# Changelog

## [2.1.3](https://github.com/diegofesanto/functions-csharp/compare/v2.1.0...v2.1.3) (2025-04-29)


### Features

* implement partially the region ([91a4516](https://github.com/diegofesanto/functions-csharp/commit/91a45164d4df2341a4b4abdfe27be9f79dcf9056))
* implement region option ([6e1a601](https://github.com/diegofesanto/functions-csharp/commit/6e1a601fc65e7359925dc1d6af924d083da4dde4))
* insert option to choose http method ([92061e6](https://github.com/diegofesanto/functions-csharp/commit/92061e6259ae07bc4048b05af51191b3a1831d87))


### Miscellaneous Chores

* **main:** release 2.1.3 ([add0b6e](https://github.com/diegofesanto/functions-csharp/commit/add0b6eabb53410fa7ad86365a555ebac361625e))
* release 2.1.0 ([165d011](https://github.com/diegofesanto/functions-csharp/commit/165d0118e25966098e6df8818ce9a4a3cb9f7096))
* release 2.1.1 ([#6](https://github.com/diegofesanto/functions-csharp/issues/6)) ([ccef16c](https://github.com/diegofesanto/functions-csharp/commit/ccef16c91ca1636baf5a5f2217fdb043dc4092e5))

## [2.1.0](https://github.com/diegofesanto/functions-csharp/compare/v2.1.0...v2.1.0) (2025-04-26)


### Features

* implement partially the region ([91a4516](https://github.com/diegofesanto/functions-csharp/commit/91a45164d4df2341a4b4abdfe27be9f79dcf9056))
* implement region option ([6e1a601](https://github.com/diegofesanto/functions-csharp/commit/6e1a601fc65e7359925dc1d6af924d083da4dde4))
* insert option to choose http method ([92061e6](https://github.com/diegofesanto/functions-csharp/commit/92061e6259ae07bc4048b05af51191b3a1831d87))


### Miscellaneous Chores

* release 2.1.0 ([165d011](https://github.com/diegofesanto/functions-csharp/commit/165d0118e25966098e6df8818ce9a4a3cb9f7096))

## [2.1.0](https://github.com/diegofesanto/functions-csharp/compare/v2.1.0...v2.1.0) (2025-04-26)


### Features

* implement partially the region ([91a4516](https://github.com/diegofesanto/functions-csharp/commit/91a45164d4df2341a4b4abdfe27be9f79dcf9056))
* implement region option ([6e1a601](https://github.com/diegofesanto/functions-csharp/commit/6e1a601fc65e7359925dc1d6af924d083da4dde4))
* insert option to choose http method ([92061e6](https://github.com/diegofesanto/functions-csharp/commit/92061e6259ae07bc4048b05af51191b3a1831d87))


### Miscellaneous Chores

* release 2.1.0 ([165d011](https://github.com/diegofesanto/functions-csharp/commit/165d0118e25966098e6df8818ce9a4a3cb9f7096))

## [2.1.0](https://github.com/diegofesanto/functions-csharp/compare/v2.0.0...v2.1.0) (2025-04-26)


### Features

* implement partially the region ([91a4516](https://github.com/diegofesanto/functions-csharp/commit/91a45164d4df2341a4b4abdfe27be9f79dcf9056))
* implement region option ([6e1a601](https://github.com/diegofesanto/functions-csharp/commit/6e1a601fc65e7359925dc1d6af924d083da4dde4))
* insert option to choose http method ([92061e6](https://github.com/diegofesanto/functions-csharp/commit/92061e6259ae07bc4048b05af51191b3a1831d87))


### Miscellaneous Chores

* release 2.1.0 ([165d011](https://github.com/diegofesanto/functions-csharp/commit/165d0118e25966098e6df8818ce9a4a3cb9f7096))

## 2.0.0 - 04-21-2024

- v2.0.0 renames this package from `functions-csharp` to `Supabase.Functions`. The depreciation notice has been set in NuGet. The API remains the same.
- Re: [#135](https://github.com/supabase-community/supabase-csharp/issues/135) Update nuget package
  name `functions-csharp` to `Supabase.Functions`

## 1.3.2 - 03-12-2024

- Re: [#5](https://github.com/supabase-community/functions-csharp/issues/5) Add support for specifying Http Timeout on a function call by adding `HttpTimeout` to `InvokeFunctionOptions`

## 1.3.1 - 06-10-2023

- Updates usage of `Supabase.Core` assembly.

## 1.3.0 - 06-10-2023

- Rename assembly to `Supabase.Functions`
- Uses `FunctionsException` instead of `RequestException`

## 1.2.1 - 11-12-2022

- Use `supabase-core` and implement `IGettableHeaders` on `Client`

## 1.2.0 - 2022-11-10

- [MINOR] `Client` now initializes with a `baseUrl` and method calls arguments are only the `functionName`.
- Included `GetHeaders` property.

## 1.1.0 - 2022-11-04

- `Client` is no longer a Singleton class, it should be initialized using a default constructor.
- [#1](https://github.com/supabase-community/functions-csharp/issues/1) Restructures library to support DI.

## 1.0.1 - 2022-04-15

- Default `token` to be `null` in `Invoke` calls to allow `Authorization` to be passed solely via Headers.

## 1.0.0 - 2022-04-14

- Initial Release
