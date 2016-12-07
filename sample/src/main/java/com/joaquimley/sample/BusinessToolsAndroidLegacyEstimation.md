# 1. Overview

The final goal of this document is to deliver an estimate for new releases of the current Business Tool apps for new Countries in the next few months.

Based on the current information, and taking into account the following assumptions,

- All points to no new releases on the short term, yet, it may be the case.
- There will be no new features.
- The UI/UX will remain the same, at most only small branding adjustments.

If the new releases were to occur there are two external dependencies that affect the plan directly:

1. API
2. Product (region specific customizations)


# 2. External Dependencies for Plan Completion

## 2.1 Product

The product changes must be taken into account, some regions have specific use cases and features, this directly affects the required time for completion.

### <a name="branding">2.1.1 Branding</a>

Do we need to support different branding? If so, what are the types of variations? colors? icons? both?

## <a name="backend">2.2 Backend</a>

### <a name="structure-backend">2.2.1 Structure</a>

Since the mobile apps are powered by the backend service for both data and the view's structure.

1. Case - Are future countries APIs the same as the Indonesia and LATAM?
2. Case - Are we to expect breaking changes on the API since when the platforms are migrated to Atlas?

Depending on the scenario, the estimated effort (below) varies considerably.

### <a name="translations-backend">2.2.2 Translations</a>

A great amount of mobile specific strings come from the backend (such as error messages). All of those strings need to be translated and agonistic to the mobile clients.

## <a name="ui-ux">2.3 UI/UX</a>

### <a name="ui-ux-resources">2.3.1 Resources</a>
If the answer for the section [2.1.2 (Product: Branding)](#branding) question is yes, the resources need to be provided and changes should always be reported.

# <a name="estimation"> 3. Estimation </a>

## <a name="definition-done">3.1 Definition of Done</a>

Our definition of when it's done should be after the following points are cleared:

- Code produced.
- Code pushed to repository and run in all flavours against the production backend.
- Development or release APK/IPA reviewed by product team, aware of each region requirements.
- Release APK/IPA passed in QA.
- APK/IPA deployed to Play Store/iTunes Store.
- Analytics data availability confirmed by BI team.

All estimations are considered done taking into account these points. If any of this is to change, this estimation has no validity whatsoever.

## <a name="time-estimation">3.2 Time estimation</a>

These estimations are not final and are based in a lot of assumptions. This will be updated when new data arrives to fulfil accurate requirements.

|Task                         |Hours|Days|
|-----------------------------|-----|----|
|Branding (Multi-brand)       |40   |5   |
|Branding (just icons, same colors)       |16   |2   |
|backend structure case 1     |16   |2   |
|backend structure case 2     |24   |4   |
|QA & Bug fixing              |40   |5   |
