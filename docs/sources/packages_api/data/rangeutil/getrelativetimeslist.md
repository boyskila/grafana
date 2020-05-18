+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "getRelativeTimesList"
keywords = ["grafana","documentation","sdk","@grafana/data"]
type = "docs"
+++

## rangeUtil.getRelativeTimesList() function

### rangeUtil.getRelativeTimesList() function

<b>Signature</b>

```typescript
export declare function getRelativeTimesList(timepickerSettings: any, currentDisplay: any): import("lodash").Dictionary<(number | {
    from: string;
    to: string;
    display: string;
    section: number;
} | (() => string) | (() => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | {
    (...items: ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (...items: ({
        from: string;
        to: string;
        display: string;
        section: number;
    } | ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>)[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((separator?: string | undefined) => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((compareFn?: ((a: {
    from: string;
    to: string;
    display: string;
    section: number;
}, b: {
    from: string;
    to: string;
    display: string;
    section: number;
}) => number) | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | {
    (start: number, deleteCount?: number | undefined): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (start: number, deleteCount: number, ...items: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => void, thisArg?: any) => void) | (<U>(callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U, thisArg?: any) => U[]) | {
    <S extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S, thisArg?: any): S[];
    (callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_1>(callbackfn: (previousValue: U_1, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_1, initialValue: U_1): U_1;
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_2>(callbackfn: (previousValue: U_2, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_2, initialValue: U_2): U_2;
} | {
    <S_1 extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(predicate: (this: void, value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S_1, thisArg?: any): S_1 | undefined;
    (predicate: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    } | undefined;
} | ((predicate: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, obj: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => number) | ((value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((target: number, start: number, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => IterableIterator<[number, {
    from: string;
    to: string;
    display: string;
    section: number;
}]>) | (() => IterableIterator<number>) | (() => IterableIterator<{
    from: string;
    to: string;
    display: string;
    section: number;
}>) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => boolean) | (<U_3, This = undefined>(callback: (this: This, value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U_3 | readonly U_3[], thisArg?: This | undefined) => U_3[]) | {
    <U_4>(this: U_4[][][][][][][][], depth: 7): U_4[];
    <U_5>(this: U_5[][][][][][][], depth: 6): U_5[];
    <U_6>(this: U_6[][][][][][], depth: 5): U_6[];
    <U_7>(this: U_7[][][][][], depth: 4): U_7[];
    <U_8>(this: U_8[][][][], depth: 3): U_8[];
    <U_9>(this: U_9[][][], depth: 2): U_9[];
    <U_10>(this: U_10[][], depth?: 1 | undefined): U_10[];
    <U_11>(this: U_11[], depth: 0): U_11[];
    <U_12>(depth?: number | undefined): any[];
})[]>;
```
<b>Import</b>

```typescript
import { rangeUtil } from '@grafana/data';
const { getRelativeTimesList } = rangeUtil;
```
<b>Parameters</b>

|  Parameter | Type | Description |
|  --- | --- | --- |
|  timepickerSettings | <code>any</code> |  |
|  currentDisplay | <code>any</code> |  |

<b>Returns:</b>

`import("lodash").Dictionary<(number | {
    from: string;
    to: string;
    display: string;
    section: number;
} | (() => string) | (() => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | {
    (...items: ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (...items: ({
        from: string;
        to: string;
        display: string;
        section: number;
    } | ConcatArray<{
        from: string;
        to: string;
        display: string;
        section: number;
    }>)[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((separator?: string | undefined) => string) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => {
    from: string;
    to: string;
    display: string;
    section: number;
} | undefined) | ((start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((compareFn?: ((a: {
    from: string;
    to: string;
    display: string;
    section: number;
}, b: {
    from: string;
    to: string;
    display: string;
    section: number;
}) => number) | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | {
    (start: number, deleteCount?: number | undefined): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
    (start: number, deleteCount: number, ...items: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | ((...items: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => number) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => boolean) | ((callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => void, thisArg?: any) => void) | (<U>(callbackfn: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U, thisArg?: any) => U[]) | {
    <S extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S, thisArg?: any): S[];
    (callbackfn: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    }[];
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_1>(callbackfn: (previousValue: U_1, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_1, initialValue: U_1): U_1;
} | {
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    (callbackfn: (previousValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => {
        from: string;
        to: string;
        display: string;
        section: number;
    }, initialValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }): {
        from: string;
        to: string;
        display: string;
        section: number;
    };
    <U_2>(callbackfn: (previousValue: U_2, currentValue: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, currentIndex: number, array: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => U_2, initialValue: U_2): U_2;
} | {
    <S_1 extends {
        from: string;
        to: string;
        display: string;
        section: number;
    }>(predicate: (this: void, value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => value is S_1, thisArg?: any): S_1 | undefined;
    (predicate: (value: {
        from: string;
        to: string;
        display: string;
        section: number;
    }, index: number, obj: {
        from: string;
        to: string;
        display: string;
        section: number;
    }[]) => unknown, thisArg?: any): {
        from: string;
        to: string;
        display: string;
        section: number;
    } | undefined;
} | ((predicate: (value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, obj: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => unknown, thisArg?: any) => number) | ((value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, start?: number | undefined, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | ((target: number, start: number, end?: number | undefined) => {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) | (() => IterableIterator<[number, {
    from: string;
    to: string;
    display: string;
    section: number;
}]>) | (() => IterableIterator<number>) | (() => IterableIterator<{
    from: string;
    to: string;
    display: string;
    section: number;
}>) | ((searchElement: {
    from: string;
    to: string;
    display: string;
    section: number;
}, fromIndex?: number | undefined) => boolean) | (<U_3, This = undefined>(callback: (this: This, value: {
    from: string;
    to: string;
    display: string;
    section: number;
}, index: number, array: {
    from: string;
    to: string;
    display: string;
    section: number;
}[]) => U_3 | readonly U_3[], thisArg?: This | undefined) => U_3[]) | {
    <U_4>(this: U_4[][][][][][][][], depth: 7): U_4[];
    <U_5>(this: U_5[][][][][][][], depth: 6): U_5[];
    <U_6>(this: U_6[][][][][][], depth: 5): U_6[];
    <U_7>(this: U_7[][][][][], depth: 4): U_7[];
    <U_8>(this: U_8[][][][], depth: 3): U_8[];
    <U_9>(this: U_9[][][], depth: 2): U_9[];
    <U_10>(this: U_10[][], depth?: 1 | undefined): U_10[];
    <U_11>(this: U_11[], depth: 0): U_11[];
    <U_12>(depth?: number | undefined): any[];
})[]>`
