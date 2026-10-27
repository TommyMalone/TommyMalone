# Tommy Malone

Software engineer in Los Angeles, 5+ years in games on C++, UI, tools, and core tech systems at ZeniMax Online Studios, EA Tiburon (Madden NFL 21 and 22), and Epic Games (Fortnite). Pursuing gameplay and game AI engineering.

tommymalonegamedev@gmail.com | [LinkedIn](https://www.linkedin.com/in/thomas-malone-34b382177)

## Start here

If you have ten minutes, start with the Gaia README's [where to start reading](https://github.com/TommyMalone/Gaia#where-to-start-reading) list. Gaia is a C# implementation of the modular AI architecture from Game AI Pro 3 (chapter 8, Dill and Dragert): utility AI and behavior-tree sequences and selectors that nest freely, NPC behavior authored in XML, an allocation-free decision cycle, written test-first and mutation-tested. The architecture was built with AI assistance under my direction; every change was reviewed by me before it entered the codebase.

- [Gaia](https://github.com/TommyMalone/Gaia): the architecture, the tests, and the authoring library in progress.
- [An_Exploration_Of_Steering_Behaviors](https://github.com/TommyMalone/An_Exploration_Of_Steering_Behaviors): Reynolds steering behaviors in UE4 and C++ (2019).
- [FIEAGameEngine](https://github.com/TommyMalone/FIEAGameEngine): a data-driven, cross-platform C++ engine from graduate coursework (2019), JSON as its config language. The core rests on [Datum](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/Datum.h), a container that types dynamically at runtime through a discriminated union, and [Scope](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/Scope.h), with their tests in [DatumTest.cpp](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/UnitTest.Library.Desktop/DatumTest.cpp) and [ScopeTest.cpp](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/UnitTest.Library.Desktop/ScopeTest.cpp). Beside them: recreated standard-library containers ([Vector](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/Vector.h), [SList](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/SList.h), [UnorderedMap](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/UnorderedMap.h)) and a family of red-black-tree containers ([RedBlackTree](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/RedBlackTree.h), [OrderedMap](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/OrderedMap.h), [OrderedSet](https://github.com/TommyMalone/FIEAGameEngine/blob/main/source/Library.Shared/OrderedSet.h)).

## Also here

- Unity Course on Game Artificial Intelligence, 01AI through 10AI : vector math, physics, A*, waypoints and graphs, navmesh, finite state machines, steering behaviors, crowd simulation.
