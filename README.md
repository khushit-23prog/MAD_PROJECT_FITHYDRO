1.1 Problem Statement
Existing commercial fitness and water tracking applications are overwhelmingly designed around cloud monetization models. Users are compelled to create third-party accounts, agree to expansive privacy policies that trade their health metrics for commercial ad targeting, and navigate bloated interfaces. Furthermore, existing solutions generally fail to dynamically synchronize physical exertion with hydration needs, ignoring the physiological reality that increased workout intensity directly demands heightened fluid intake. There is an acute demand for a lean, robust, privacy-first Native Android application that functions completely offline without subscription barriers or battery-draining telemetry.

1.2 Project Objectives
The primary goal of this project is to architect, develop, and test FitHydro Tracker, an offline native mobile application. Specific objectives include:
1. Rapid Input Processing: Enable users to log fluid intake in under two seconds through standardized preset containers (250ml, 500ml, 750ml) and custom inputs.
2. Adaptive Goal Computation: Formulate and implement a scientific hydration calculator factoring in user weight and activity levels.
3. Integrated Activity Tracking: Provide multi-modal workout logging that translates exercise duration into caloric burn.
4. Relational Data Persistence: Store historical activity feeds using Android SQLite with full CRUD capabilities.
5. Interactive User Experience: Implement fluid visual animations using Material 3 and custom Canvas progress bars.

1.3 Scope & Limitations
The current scope encompasses smartphones and tablets running Android 7.0 (API Level 24) through Android 14 (API Level 34). All calculations, database transactions, and streak computations execute strictly on-device. Limitations of the initial release include the deliberate absence of cloud-based multi-device synchronization and automated wearable sensor polling, prioritizing absolute user privacy, zero battery consumption, and simplicity.
