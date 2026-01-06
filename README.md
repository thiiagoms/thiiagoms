# thiiagoms@freedom $: echo 'Hello friend ![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/68281298/119243223-2ac5c200-bb3b-11eb-9d6f-2b6d98fa3c9e.gif)'

```php
<?php

declare(strict_types=1);

final class Thiiagoms
{
    private(set) string $role = 'Backend Developer';
    private(set) string $baseLocation = 'Brazil';

    private(set) array $availability = ['Remote', 'Hybrid in Belo Horizonte', 'On-site in Belo Horizonte'];

    private(set) array $mainStack = ['PHP', 'Python', 'Laravel/Lumen', 'Symfony'];

    private(set) array $otherLanguages = ['JavaScript', 'TypeScript', 'Go', 'Kotlin', 'Bash'];

    private(set) array $frameworks = [
        'Laravel',
        'Lumen',
        'Symfony',
        'Slim',
        'Quarkus',
        'Django',
        'FastAPI'
    ];

    private(set) array $cloud = ['AWS', 'Heroku'];

    private(set) array $architecture = [
        'Microservices',
        'Event-Driven Architecture',
        'Clean Architecture',
        'Design Patterns'
    ];

    private(set) array $engineeringPractices = [
        'Clean Code',
        'SOLID',
        'KISS',
        'Automated Tests',
        'Code Reviews'
    ];

    private(set) array $security = [
        'Application Security',
        'OWASP',
        'Vulnerability Management',
        'Static Code Analysis'
    ];

    private(set) array $data = [
        'sql' => [
            'PostgreSQL',
            'MySQL'
        ],
        'nosql' => [
            'MongoDB',
            'Redis'
        ],
        'messaging' => [
            'RabbitMQ'
        ]
    ];

    /** @var string[] */
    private(set) array $delivery = ['Docker', 'CI/CD', 'Jenkins', 'Git', 'GitHub Actions'];

    public function links(): array
    {
        return [
            'linkedin' => 'https://linkedin.com/in/thiiagoms',
            'github' => 'https://github.com/thiiagoms',
        ];
    }
}

