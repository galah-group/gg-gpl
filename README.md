# Galah Group General Public License

The Galah Group General Public License is a deriavitive of the [GNU Affero General Public License version 3 (AGPLv3)](http://www.gnu.org/licenses/agpl.html).

The GG-GPL is not a Free Software license, nor is it an Open Source license.

## Quick Overview

**You are free to...**

 * view, share, and distribute the source code freely.
 * run the program.
 * create deriavitive works.

**With the conditions...**

 * you must provide a way for users who interact with the program a way to get the source code.
 * **you cannot deploy the work such that more than 15 users have access to it.**
 * deriavitive works are licensed under the same license.

*Disclaimer: This overview is a convenient human-readable summary of the license. This overview is not a part of the GG-GPL and has no legal merit.*

## FAQ

### Why did you make this license?

I maintain [a piece of software](https://github.com/galah-group/galah) that I would like to make money from. Initially, I figured I could just sell support. But after some time I realized I didn't really like that idea.

I want to make the documentation I provide excellent, I want my testing to detect any problems well before a user sees them, I want an error reporting system that is easy to access for anyone, and I want my software to be as easy to deploy as possible. If I charge for support I would feel conflicted when writing public documentation, and detecting problems before they ever get in production would be less of a priority because such problems would be a source of income. Additionally, the more difficult my program is to deploy, the higher the chance someone will want to pay for support.

These potential conflicts worried me greatly, so I decided to try something different, something new. I do not know if this business model will work. As far as I can tell, a piece of software under licensing terms like this has never been released. Regardless of my own personal success or failure though, I think that this license fills a hole in the collection of fantastic licenses that currently exist, and I hope that it will be useful to others.

### How do I apply this to my own work?

In order for you to be able to provide an exception to the maximum user limitation you will need to have copyright on the entire code base. If your code base is owned entirely by your company, this is not a problem. If your code base is owned by a large number of contributers, this may pose a problem. In the latter case, you may want to draft a contributers agreement that gives you or your company the ability to except certain users from the maximum user limitation.

As far as actually applying the license to your code, because this license has a lot in common with the AGPLv3, a useful resource is the [GNU's guide for applying the GPL to your own work](http://www.gnu.org/licenses/gpl-howto.html).

It basically boils down to including the license text in your repository, then adding copyright notices to your files. An example file header is...

> Copyright YEAR You  
> Copyright YEAR Other contributers as noted in the CONTRIBUTERS file
>
> This file is part of Project.
>
> You can redistribute Project and/or modify it under the terms of the Galah Group General Public License as published by Galah Group LLC, either version 1 of the License, or (at your option) any later version.
>
> Project is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the Galah Group General Public License for more details.
>
> You should have received a copy of the Galah Group General Public License along with Project.  If not, see <http://www.galahgroup.com/gg-gpl>.

### Why is the GG-GPL not considered a Free License?

The Free Software Foundation lists four fundamental freedoms that makes free software free ([source](http://www.gnu.org/philosophy/free-sw.html)).

 > * The freedom to run the program, for any purpose (freedom 0).
 > * The freedom to study how the program works, and change it so it does your computing as you wish (freedom 1). Access to the source code is a precondition for this.
 > * The freedom to redistribute copies so you can help your neighbor (freedom 2).
 > * The freedom to distribute copies of your modified versions to others (freedom 3). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.

Freedoms 1, 2, and 3 are preserved when you license your software with the GG-GPL, but freedom 0 (arguably the most important freedom) is not preserved. When code is licensed under the GG-GPL users will be required to gain permission from you to use your software in a commercially viable manner.

### Why is the GG-GPL not considered an Open Source License?

The Open Source Initiative defines 10 conditions on Open Source licenses ([source](http://opensource.org/osd)).

 > 1. Free Redistribution
 > 2. Source Code
 > 3. Derived Works
 > 4. Integrity of The Author's Source Code
 > 5. No Discrimination Against Persons or Groups
 > 6. No Discrimination Against Fields of Endeavor
 > 7. Distribution of License
 > 8. License Must Not Be Specific to a Product
 > 9. License Must Not Restrict Other Software
 > 10. License Must Be Technology-Neutral

Condition 6 is not satisfied by the GG-GPL. Specifically, condition 6 mandates that...

 > The license must not restrict anyone from making use of the program in a specific field of endeavor. For example, it may not restrict the program from being used in a business, or from being used for genetic research.

The GG-GPL attempt to restrict users from making use of the program in a commercially viable way without getting permission from the copyright holder.
