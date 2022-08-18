```php
<?php
namespace JQuevedo82;
class About extends Me
{
	  /* Personalinformation */ 
    public function getCurrentPersonalinformation()
    {
        return [
            'personalinformation' => [
                'name' => 'Jose G. Quevedo C.',
                'title' => 'Ingeniero en Informatica',
                'nationality' => 'VEN',
                'resident' => 'Buenos Aires. ARG',
		'mytwitter' => '@jquevedo82',
		'mylinkedin' => 'https://www.linkedin.com/in/jquevedo82/'
            ]
        ];
    }
  	/* Workplace */ 
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'NEUMEN',
                'pageWeb' => 'https://autoneumen.com/neumen/',
                'position' => 'Full Stack Developer',    
            ]
        ];
    }
    /* Primary skills/knowledge */
    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Angular::class,
            NodoJs::class,
            NestJs::class,
            Mysql::class,
        ];
    }
	
	/* Relevant goal */
    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```

