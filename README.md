- 👋 Hi, I’m @niteshgupta2711
- 👀 I’m interested in Artificial Intelligence, Big data, Machine learning, AIops
- 🌱 I’m currently looking for job opportunities.
- 💞️ I’m looking to collaborate on 
- 📫 How to reach me https://www.linkedin.com/in/nitesh-kumar-gupta-6847b9218/
- Here is my website https://aiwave.herokuapp.com/ for my projects


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

<!---
niteshgupta2711/niteshgupta2711 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
