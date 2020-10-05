# Change Log

## 1.0.0

### beta-3
- Allow setting unsubscribe headers,
  see [#24](https://github.com/stomp-js/rx-stomp/issues/24)
  and [#254](https://github.com/stomp-js/rx-stomp/pull/254).
- Option to subscribe only once, i.e., to not auto resubscribe.
  see [#5](https://github.com/stomp-js/rx-stomp/issues/5)
  and [#254](https://github.com/stomp-js/rx-stomp/pull/254).

### beta-2
- Generate only ES2017 and UMD packages.
- Concept of `discardWebsocketOnCommFailure`.
- Update documentation links as per new URL structure without dates.

## 0.3.5 (2020-04-05)

- Pass `client` to beforeConnect callback.
  Fixes [#204](https://github.com/stomp-js/rx-stomp/issues/204).

## 0.3.4 (2019-10-10)

- Fix webpack config - window not defined in nodejs.
- Expose `active` property.

## 0.3.3 (2019-08-22)

- Support for user supplied correlation id in RxStompRPC.
  Fixes [#129](https://github.com/stomp-js/rx-stomp/issues/129).

## 0.3.2 (2019-06-12)

- Supports `stompjs@5.4.2`.

## 0.3.1 (2019-06-02)

- Updates in contributing guidelines.
- Mark streams as ReadOnly in RxStomp.
  See [rx-stomp/pull/93](https://github.com/stomp-js/rx-stomp/pull/93).
  Many thanks [Ray Booysen](https://github.com/raybooysen).
- Option to not enqueue a message if broker is not connected.
  See [rx-stomp/pull/94](https://github.com/stomp-js/rx-stomp/pull/94).
  Many thanks [Ray Booysen](https://github.com/raybooysen).

## 0.3.0-beta.1 (2019-01-20)

- Promote 0.3.0-beta.1 to 0.3.0

## 0.3.0-beta.1 (2019-01-17)

- Expose options from @stomp/stompjs@5.2.0 -
  splitLargeFrames and forceBinaryWSFrames.

## 0.2.0 (2019-01-10)

- None.

## 0.2.0-beta.1 (2018-12-24)

- Update "@stomp/stompjs" dependency to 5.1.0.
- Travis build - test ng2-stompjs with current build.
- Travis build - test lint as well.
- beforeConnect supports async callbacks.
- Update to IFrame, IMessage, ITransaction interfaces.
- Concept of unhandledFrame$ and webSocketError$.
- Support for logRawCommunication, fixes
  [rx-stomp/issues/25](https://github.com/stomp-js/rx-stomp/issues/25)
- Update other dependencies to latest versions.
- On a reconnect - ensure subscriptions are established before
  publishing outstanding messages.
  Fixes [rx-stomp/issues/4](https://github.com/stomp-js/rx-stomp/issues/4)

## 0.1.1 (2018-11-26)

- Update @stomp/stompjs to 5.0.2.
- Align constant values in RxStompState with WebSocket.
  Fixes [stomp-js/rx-stomp#7](https://github.com/stomp-js/rx-stomp/issues/7).
- Updated reference to samples and documents.

## 0.1.0 (2018-11-12)

- Documentation

## 0.1.0-beta.5 (2018-11-10)

- Change in packaging, UMD is now default.

## 0.1.0-beta.4 (2018-11-02)

- Rolled back beta.3
- Align with underlying library: waitForReceipt --> watchForReceipt

## 0.1.0-beta.3 (2018-10-30)

- Failed, rolled back

## 0.1.0-beta.2 (2018-10-28)

- Uses @stomp/stompjs v5 properly
- Initial documentation
- Refactors and renames
- tslint clean
- Refactored specs

## 0.1.0-beta.1 (2018-10-13)

- Factored out from https://github.com/stomp-js/ng2-stompjs
- Build/test/doc systems are working
- Travis is setup
