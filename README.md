# Maki

<img src="https://github.com/vladris/Maki/blob/master/maki.jpg" width="300">

A type library with .NET and Java versions.

## Maki.NET

[On GitHub](https://github.com/vladris/Maki.NET) | [Website](https://vladris.com/Maki.NET) | [NuGet](https://www.nuget.org/packages/Maki)

<details>
  <summary>Types</summary>
  
### Types

Maki provides discriminate union types ``Variant<...>`` and ``Either<TLeft, TRight>``, a ``NotNull`` container, ``Optional`` and ``Error`` monads, primitive types ``Unit`` and ``Never``.

### Functional Extensions

``Maki.Functional`` provides extension methods to convert ``Action<...>`` to an equivalent ``Func<..., Unit>`` and extension methods for ``Func<...>`` to enable currying.
</details>

## Maki.Java

[On GitHub](https://github.com/vladris/Maki.Java) | [Website](https://vladris.com/Maki.Java)

<details>
  <summary>Types</summary>
  
### Types

Maki provides discriminate unions of up to 8 types (``Variant1<T1>``, ``Variant2<T1, T2>`` ... ``Variant8<T1, T2, ...>``), ``Unit`` and ``Never``, an ``Either<TLeft, TRight>`` union and an ``Error<T>`` monad.
</details>
