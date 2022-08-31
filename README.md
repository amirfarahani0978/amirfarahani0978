### 👋 Hi there ,I'm Amirhossein

<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Founder'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
<!--
**amirfarahani0978/amirfarahani0978** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
Here are some ideas to get you started:
🔭 I’m currently working on ...
🌱 I’m currently learning ....
👯 I’m looking to collaborate on ...
🤔 I’m looking for help with ...
💬 Ask me about ...
📫 How to reach me: ...
😄 Pronouns: ...
⚡ Fun fact: ...
-->
