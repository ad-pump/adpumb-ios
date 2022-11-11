# Adpumb

version 2.0.0

Change Log:

- Google Mobile Ads SDK Migration
- Removed public methods:
  - AdDisplayManager.updatePresenter()
  - AdDisplaymanger.updateContext()
- Method Signature Change:
  - public func showAd(viewController: UIViewController, adCompletionHandler: AdPumbDelegate?, placementOptions: PlacementOptions)
  to public func showAd(adCompletionHandler: AdPumbDelegate?, placementOptions: PlacementOptions)
