layout: page
title: "Talks"
permalink: /URL-PATH

# Android Makers 2024

## Tap it! Shake it! Fling it! Sheep it! - The Compose Gesture Animations Dance! | Nicole Terc
Workshop avout Compose animations
* [Youtube replay](https://www.youtube.com/watch?v=AOV9CrYAexQ)
* [Github repo of the workshop](https://github.com/nicole-terc/composable-sheep)
* [Github repo about gestures](https://github.com/nicole-terc/sheepit-gestures/tree/main)

**Notes**
using graphicsLayer on Animatable for performance instead of scale method: avoid whole recompostion by executing only the lambda
snapTo: move to value straight without animation
registerlisterner: make sure to unscubscribe from system on pause or stop
refaire le codelab au calme à la maison

##  The complete guide to Compose animations | Eliza Camber
* [Youtube replay](https://www.youtube.com/watch?v=2EHcaxtL1sM&list=PLn7H9CUCuXAtxPltq2mEHc_Wbgckrd4B-&index=5)

## Structuring modules in an Android app project | Kinnera Priya Putti
* [Youtube replay](https://www.youtube.com/watch?v=dSCNkNeg5Pk)

**Notes**
check the 2 tools she talked about, re-check the basic module separation

## Some relevant librairies
* [Curation of Kotlin Multiplatform libs](https://github.com/AAkira/Kotlin-Multiplatform-Libraries)
* [Other curation of Kotlin Multiplatform libs](https://github.com/terrakok/kmp-awesome)
* [Swift Kotlin Interface Enhancer](https://github.com/touchlab/SKIE)
* [Apollo Kotlin GraphQL](https://github.com/apollographql/apollo-kotlin)

## Cache once and use everywhere | Sinan Kozak
* [Slides](https://speakerdeck.com/kozaxinan/cache-once-and-use-everywhere)
* [Youtube replay](https://www.youtube.com/watch?v=_UnRVsvGSjg)


## From Developer to InvestiGITor: Cracking the Case at AndroidMakers 2024
* [Slides](https://drive.google.com/file/d/1H1yDnnq1ZK1PQDfQhtrFG5IwnMeRf-xZ/view)
* [Blog summary](https://medium.com/bforbank-tech/from-developer-to-investigitor-cracking-the-case-at-androidmakers-2024-b10cf6428d35)
* [Youtube replay](https://www.youtube.com/watch?v=xVaIM0yD0SM)

**Notes**
read sum up

## Building libraries for the next 25 years | Martin Bonnin
* [Youtube replay](https://www.youtube.com/watch?v=y9_i0utqTCw)
* [Kotlin and exceptions Medium](https://elizarov.medium.com/kotlin-and-exceptions-8062f589d07)

**Notes**
ream roman elizarov kotlin and exceptions medium post
what is supply chain?

## Three ways to use AI on Android: The Good, the Bad and the Ugly | Marcel Pinto Biescas
* [Slides](https://speakerdeck.com/marxallski/three-ways-to-use-ai-on-android-the-good-the-bad-and-the-ugly)
* [Youtube replay](https://www.youtube.com/watch?v=IJgYBuL6-s4)

## Ton app en KMP dans la vraie vie : notre méthode en 7 étapes | Baptiste Carlier & Antoine Robiez
* [Slides](https://speakerdeck.com/bapness/ton-app-en-kmp-dans-la-vraie-vie-notre-methode-en-7-etapes?slide=17)
* [Youtube replay](https://www.youtube.com/watch?v=AckQ3zAl954)

**Notes**
astuce ios: plugin touchlab pour faire l'interface objective c swift
decoupage des étapes
créer son module commun
migrer domain en retrouvant les équivalents kotlin des classes java utilisés (java.util.data par ex)
couche data en migrant vers des bibl kmp
migrer les ressources en utilisant moko resources
migrer les injections en utilisant koin en plus de dagger hilt
écrire la présentation ios
les étapes peuvent être faires dans le désordre
utiliser des extensions pour migrer progressivement la couche domain

## Hitchhiker's Guide to Kotlin/Compose Multiplatform samples and libraries | John O’Reilly
* [Slides](https://speakerdeck.com/joreilly/compose-multiplatform-samples-and-libraries-androidmakers-2024)
* [Youtube replay](https://www.youtube.com/watch?v=znrE7j9L0yE)

## Bytecode analysis for everyone! | Konstantin Zolotov
* [Youtube replay](https://www.youtube.com/watch?v=6cYmdoeZ1OY)
* [Medium blog post](https://medium.com/bumble-tech/crafting-android-bytecode-analysis-tooling-using-a-secret-ingredient-part-1-13e2d5a65113)

**Notes**
read article

## Unblocking The Main Thread: Solving ANRs and Frozen Frames | Sinan Kozak
* [Youtube replay](https://www.youtube.com/watch?v=BSB7ZLNm9ac)
* [Slides](https://fr.slideshare.net/slideshow/unblocking-the-main-thread-solving-anrs-and-frozen-frames/267562738)

**Notes**
dig the tools listed

## Behind the mirror, Kotlin reflection | Danny Preussler
* [Youtube replay](https://www.youtube.com/watch?v=jR1SXJcGcMs)

**Notes**
A voir

## Demystifying CTFs - manipulating Android apps | Merab Tato Kutalia
* [Youtube replay](https://www.youtube.com/watch?v=FTRPdQ0e11U)
* [OWASP crackmes for learning](https://mas.owasp.org/crackmes/)

**Notes**
check owasp top 10 Vulnerabilities
frida lib dynamic application security testing (DAST)
software composition analysis ?
fuzzing: random input to test behaviour of the application
static application security testing like sonar
security checklist owasp mastg
writeup: post explaining how you solved the problem. he wrote some
hackthebox.com challenges saw -> popular ctf chanllenge website
basic generalist tools: jadx, apktool, ida/ghidra, frida

## Misc. blog posts to read
* [Modern Android Development in 2024 Medium blog post](https://devjorgecastro.medium.com/modern-android-development-in-2024-b70f194938bd)
* [What is R8 and how we enabled it Medium blog post](https://stefma.medium.com/what-is-r8-and-how-we-enabled-it-4f5764a7ff9c)
