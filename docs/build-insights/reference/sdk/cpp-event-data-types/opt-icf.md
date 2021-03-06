---
title: "OptICF class"
description: "The C++ Build Insights SDK OptICF class reference."
ms.date: "02/12/2020"
helpviewer_keywords: ["C++ Build Insights", "C++ Build Insights SDK", "OptICF", "throughput analysis", "build time analysis", "vcperf.exe"]
---
# OptICF class

::: moniker range="<=vs-2015"

The C++ Build Insights SDK is compatible with Visual Studio 2017 and above. To see the documentation for these versions, set the Visual Studio version selector control for this article to Visual Studio 2017 or Visual Studio 2019.

::: moniker-end
::: moniker range=">=vs-2017"

The `OptICF` class is used with the [MatchEvent](../functions/match-event.md), [MatchEventInMemberFunction](../functions/match-event-in-member-function.md), [MatchEventStack](../functions/match-event-stack.md), and [MatchEventStackInMemberFunction](../functions/match-event-stack-in-member-function.md) functions. Use it to match an [OPT_ICF](../event-table.md#opt-icf) event.

## Syntax

```cpp
class OptICF : public Activity
{
public:
    OptICF(const RawEvent& event);
};
```

## Members

Along with the inherited members from its [Activity](activity.md) base class, the `OptICF` class contains the following members:

### Constructors

[OptICF](#opt-icf)

## <a name="opt-icf"></a> OptICF

```cpp
OptICF(const RawEvent& event);
```

### Parameters

*event*\
An [OPT_ICF](../event-table.md#opt-icf) event.

::: moniker-end
