
```php

use Manuskript\Manuskript;


Manuskript\Editor::make('About Me')
  ->fieldset('person', [
    Manuskript\Fields\Text::make('Name'),    // Tobias
    Manuskript\Fields\HasOne::make('Job'),   // {"title": "software developer", "company": "manuskript"}
    Manuskript\Fields\Asset::make('Avatar'), // https://avatars.githubusercontent.com/u/2782913
  ]);

```
