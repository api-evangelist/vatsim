# VATSIM

VATSIM (Virtual Air Traffic Simulation Network) is a global online flight simulation network providing real-time data about pilots, controllers, flight plans, and ATC positions. The VATSIM REST APIs allow developers to access live network data, member statistics, aviation weather, upcoming events, and authentication services for the simulation community.

**Developer Hub:** https://vatsim.dev/services/apis/

## APIs

| API | Base URL | Auth | Description |
|-----|----------|------|-------------|
| Core API | https://api.vatsim.net/v2 | APIv2 Key | Member data, ratings, statistics, ATC positions |
| Data API | https://data.vatsim.net | None | Live network feed — pilots, controllers, ATIS (15s refresh) |
| Events API | https://api.vatsim.net/v2/events | None | Upcoming VATSIM network events |
| METAR API | https://metar.vatsim.net | None | Real-time airport weather (METAR) by ICAO code |
| Connect API | https://auth.vatsim.net | OAuth2 | Single sign-on for VATSIM members |
| Slurper API | https://api.vatsim.net/v2 | None | Real-time user connection data |

## Resources

- [APIs.json](apis.yml)
- [Plans](plans/plans.yml)
- [Rate Limits](rate-limits/rate-limits.yml)
- [FinOps](finops/finops.yml)
- [VATSIM Developer Documentation](https://vatsim.dev/)
- [VATSIM User Agreement](https://vatsim.net/docs/policy/user-agreement)
