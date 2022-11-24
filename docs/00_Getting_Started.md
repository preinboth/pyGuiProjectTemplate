[TOC]

---

## Voraussetzungen

---
SAP 7.50
abapGit
abapAppl [Github](https://github.com/abapTools/abapAppl)


---

## Feature

---

abapDPG

---

## Konfiguration

---



---

## Examples

---




---

## Entwurfsmuster

---

### Erzeugungsmuster ( Creational Patterns )

Erzeugungsmuster abstrahieren Objekterzeugungsprozesse. Klassenmuster nutzen dabei Vererbung, um die Klasse des zu
erzeugenden Objekts zu variieren. Objektmuster delegieren die Objekterzeugung an andere Objekte.

#### Klassenmuster

- [Fabrikmethode (factory method)](80_Design_Pattern/82_creational_patterns/factory_method.md)

#### Objektmuster

* [Abstrakte Fabrik (abstract factory)](80_Design_Pattern/82_creational_patterns/abstract_factory_pattern.md)
* [Einzelstück (singleton)](80_Design_Pattern/82_creational_patterns/singleton_pattern.md)
* [Erbauer (builder)](80_Design_Pattern/82_creational_patterns/builder_pattern.md)
* [Prototyp (prototype)](80_Design_Pattern/82_creational_patterns/prototype_pattern.md)

### Strukturmuster ( Structural Patterns )

Strukturmuster fassen Klassen und Objekte zu größeren Strukturen zusammen. Klassenmuster fassen dabei Schnittstellen (
Typen) und Implementierungen (Klassen) zusammen, während Objektmuster Objekte in eine Struktur einordnen. Durch
Klassenmuster beschriebene Strukturen sind zur Übersetzungszeit festgelegt. Die durch Objektmuster beschriebenen
Strukturen sind zur Laufzeit änderbar.

#### Klassenmuster

* [Adapter (adapter) (Adapter mit Vererbung oder Klassenadapter)](80_Design_Pattern/83_structural_patterns/adapter_pattern_class.md)

#### Objektmuster

* [Adapter  (adapter) (Adapter mit Assoziation oder Objektadapter)](80_Design_Pattern/83_structural_patterns/adapter_pattern_assoziation.md)
* [Brücke (bridge, handle/body)](80_Design_Pattern/83_structural_patterns/bridge_pattern.md)
* [Dekorierer (decorator)](80_Design_Pattern/83_structural_patterns/decorator_pattern.md)
* [Fassade (facade)](80_Design_Pattern/83_structural_patterns/facade_pattern.md)
* [Fliegengewicht (flyweight)](80_Design_Pattern/83_structural_patterns/flyweight_pattern.md)
* [Kompositum (composite)](80_Design_Pattern/83_structural_patterns/composite_pattern.md)
* [Stellvertreter (proxy, surrogate)](80_Design_Pattern/83_structural_patterns/proxy_pattern.md)

### Verhaltensmuster ( Behavioral Patterns )

Verhaltensmuster beschreiben die Interaktion zwischen Objekten und komplexen Kontrollflüssen. Klassenmuster teilen die
Kontrolle auf verschiedene Klassen auf, Objektmuster nutzen Komposition an Stelle von Vererbung.
Die Verhaltensmuster können in verschiedene Gruppen unterteilt werden. Bei den funktionalen Verhaltensmuster werden
beispielsweise Zustandsmuster, Data Building Muster, und Flusssteuerungsmuster unterschieden.

#### Klassenmuster

* [Interpreter (interpreter)](80_Design_Pattern/81_behavioral_patterns/interpreter.md)
* [Schablonenmethode (template method)](80_Design_Pattern/81_behavioral_patterns/template_method.md)

#### Objektmuster

* [Beobachter (observer, dependents, publish-subscribe, listener)](80_Design_Pattern/81_behavioral_patterns/observer.md)

* [Besucher (visitor)](80_Design_Pattern/81_behavioral_patterns/visitor_pattern.md)

* [Iterator (iterator, cursor)](80_Design_Pattern/81_behavioral_patterns/iterator_pattern.md)

* [Kommando (Befehl, command, action, transaction)](80_Design_Pattern/81_behavioral_patterns/command_pattern.md)

* [Memento (memento, token)](80_Design_Pattern/81_behavioral_patterns/memento_pattern.md)

* [Strategie (strategy, policy)](80_Design_Pattern/81_behavioral_patterns/strategy_pattern.md)

* [Vermittler (mediator)](80_Design_Pattern/81_behavioral_patterns/mediator_pattern.md)

* [Zustand (state, objects for state)](80_Design_Pattern/81_behavioral_patterns/state_pattern.md)

* [Zuständigkeitskette (chain of responsibility)](80_Design_Pattern/81_behavioral_patterns/chain_of_responsibility_pattern.md)

### Muster für objektrelationale Abbildung

### Muster für Nachrichtenübermittlung (Messaging Patterns)
