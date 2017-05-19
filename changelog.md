# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.7.0 YT-DEV]
### Added
- Applied client modification detection
- Applied chat filter
- Treadmills have been temporarily removed, see below for more details
- Work on new prison jobs has started, but will not be finished in this update
- Players that are enrolled in a job now have their freetime displayed as work
- Players that are enrolled in a job can now only work during their freetime
- Activities between 2200 and 0500 hours (10PM-5AM) are being looked into, the possibility of completely skipping the night period is also being considered

### Changed
- Removed artificial neural network implemented in about [1.6.0 YT-STABLE]
- Applied fix to prevent money duplication

Treadmills are a noticeably experimental feature, and are constantly being tweaked with. Through trial and error, it's been concluded that we cannot knockback or bounce the player, however the solution we're using can (not as often) cause the same glitch as bouncing them.

In 1.7.0 we are updating the treadmill class to allow more control for the player using it, some updates include the player being able to change the treadmill speed (examples of a higher speed would be an increased chance of the player receiving a temporary blindness effect, to simulate running long distances in real life), others would be a higher multiplier of how fast the players speed and stamina would increase.

(1.0.X to 1.6.7 are not public, any major updates are listed in 1.7.0)

## [1.0.1 BETA]
### Added
- Added a fix to innocent detection.
Notes: Inmates causing trouble (showing off contraband, fighting, etc) will have a timer until they're innocent again. Guard can only handcuff an inmate while they're not innocent. This also means that guard abuse detection can also be enabled as it didn't previously work due to this.

## [1.0.0 BETA]
### Added
- Money system added.
- Cash system added.
- Contraband shop added.
- Inmate team can close if there are not enough guards playing.
- ID cards added to allow entry to secure areas.

### Changed
- Gate opening and closing causing lag should be fixed.
- Tags should be fixed.
- Kill streaks now reward cash for 2 consecutive or more kills.
- Kill streaks now reward a variety of items or weapons for 2 consecutive or more kills.
- (?) Guards now have a chance of dropping cash on death.


## [0.0.60 BETA]
### Added
- Chat formatting based on group.
- Chat tags for ExileWeb Limited employees and VIP's.
- All gates close when the server is first started.

### Changed
- Gate oppening and closing times have changed to prevent players being trapped in areas.
- Investigating cause of lag when gates update.

