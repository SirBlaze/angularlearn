## Day 1 (22.12.2019)
- Projektstart!
- Tools:
    - Visual Studio Code (HTML preview extension)
- Languages: 
    - Markdown
    - HTML
    - CSS
- Website: Erster Prototyp mit Platzhaltern fertig


## Day 2 (29.12.2019)
- Getting started with Angular
    ### The theory (what Angular contains / manages)
    - HTML: Will determine the website element layout
    - CSS: Will determine the website styles
    - JavaScript: Can run logic
    - TypeScript: Typed JavaScript language that compiles into JavaScript

- Tools
    - Angular (*npm i -g angular-cli*)
    - PowerShell (navigation via *cd* and *ls*)
    - Node.js: https://nodejs.org/en/download/
    - npm package management (npm i)

- Links
    - Angular setup: https://angular.io/guide/setup-local
    - Angular tutorial: https://angular.io/tutorial/toh-pt0
    - Where we stopped: https://angular.io/tutorial/toh-pt1#edit-the-hero

- Object oriented programming (OOP) example
    - Classes (e.g. 'Auto')
    - Methods (e.g. 'Fahren')
    - Properties (e.g. 'Hersteller')
    - Try out at: https://dotnetfiddle.net/ (C#)

    ```
    using System;
                        
    public class Program
    {
        public static void Main()
        {
            var meinAuto = new Auto("Ferrari");
            var meinZweitesAuto = new Auto("Ferrari");
            
            meinAuto.Fahren(97.0);
            meinZweitesAuto.Fahren(47.0);
            
            Console.WriteLine(meinAuto.Hersteller + ": " + meinAuto.Kilometerstand);
            Console.WriteLine(meinZweitesAuto.Hersteller + ": " + meinZweitesAuto.Kilometerstand);
        }
    }


    public class Auto {
        public string Hersteller;
        public int Reifen = 4;
        public double Kilometerstand = 3.0;
        
        public Auto(string Hersteller){
            this.Hersteller = Hersteller;
        } 
        
        public void Fahren(double WieViel){
            this.Kilometerstand = this.Kilometerstand + WieViel;
        }
    }
    ```

## Day 3 (12.01.2020)
- Git
    - Tools
        - Git
        - Tortoise Git
    
    - How to work with Git:
        1. Create a *repository*
        2. *Add* files that should be *tracked*
        3. *Commit* changes to the *local* repository
        4. *Push* changes to the *remote* repository


    