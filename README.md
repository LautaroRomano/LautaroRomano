### Hi there 👋

<p>'<?php'<br>

namespace LautaroRomano;<br>

class About extends Me<br>
{<br>
    public function getCurrentWorkplace(): array<br>
    {<br>
        return [
            'workplace' => []
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            ReactNative::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
</p>
