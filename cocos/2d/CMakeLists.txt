if(WIN32)

ADD_DEFINITIONS(-DUNICODE -D_UNICODE)

set(COCOS_2D_PLATFORM_SRC
  2d/platform/win32/CCStdC.cpp
  2d/platform/win32/CCFileUtilsWin32.cpp
  2d/platform/win32/CCCommon.cpp
  2d/platform/win32/CCApplication.cpp
  2d/platform/desktop/CCGLView.cpp
  2d/platform/win32/CCDevice.cpp
)

elseif(APPLE)

else()

set(COCOS_2D_PLATFORM_SRC
  2d/platform/linux/CCStdC.cpp
  2d/platform/linux/CCFileUtilsLinux.cpp
  2d/platform/linux/CCCommon.cpp
  2d/platform/linux/CCApplication.cpp
  2d/platform/desktop/CCGLView.cpp
  2d/platform/linux/CCDevice.cpp
)

endif()


set(COCOS_2D_SRC
  2d/ccFPSImages.c
  2d/CCAction.cpp
  2d/CCActionCamera.cpp
  2d/CCActionCatmullRom.cpp
  2d/CCActionEase.cpp
  2d/CCActionGrid.cpp
  2d/CCActionGrid3D.cpp
  2d/CCActionInstant.cpp
  2d/CCActionInterval.cpp
  2d/CCActionManager.cpp
  2d/CCActionPageTurn3D.cpp
  2d/CCActionProgressTimer.cpp
  2d/CCActionTiledGrid.cpp
  2d/CCActionTween.cpp
  2d/CCAnimation.cpp
  2d/CCAnimationCache.cpp
  2d/CCAtlasNode.cpp
  2d/CCClippingNode.cpp
  2d/CCComponent.cpp
  2d/CCComponentContainer.cpp
  2d/CCDrawNode.cpp
  2d/CCDrawingPrimitives.cpp
  2d/CCFont.cpp
  2d/CCFontAtlas.cpp
  2d/CCFontAtlasCache.cpp
  2d/CCFontCharMap.cpp
  2d/CCFontFNT.cpp
  2d/CCFontFreeType.cpp
  2d/CCGLBufferedNode.cpp
  2d/CCGrabber.cpp
  2d/CCGrid.cpp
  2d/CCIMEDispatcher.cpp
  2d/CCLabel.cpp
  2d/CCLabelAtlas.cpp
  2d/CCLabelBMFont.cpp
  2d/CCLabelTTF.cpp
  2d/CCLabelTextFormatter.cpp
  2d/CCLayer.cpp
  2d/CCMenu.cpp
  2d/CCMenuItem.cpp
  2d/CCMotionStreak.cpp
  2d/CCNode.cpp
  2d/CCNodeGrid.cpp
  2d/CCParallaxNode.cpp
  2d/CCParticleBatchNode.cpp
  2d/CCParticleExamples.cpp
  2d/CCParticleSystem.cpp
  2d/CCParticleSystemQuad.cpp
  2d/CCProgressTimer.cpp
  2d/CCRenderTexture.cpp
  2d/CCScene.cpp
  2d/CCScriptSupport.cpp
  2d/CCSprite.cpp
  2d/CCSpriteBatchNode.cpp
  2d/CCSpriteFrame.cpp
  2d/CCSpriteFrameCache.cpp
  2d/CCTMXLayer.cpp
  2d/CCTMXObjectGroup.cpp
  2d/CCTMXTiledMap.cpp
  2d/CCTMXXMLParser.cpp
  2d/CCTextFieldTTF.cpp
  2d/CCTexture2D.cpp
  2d/CCTextureAtlas.cpp
  2d/CCTextureCache.cpp
  2d/CCTileMapAtlas.cpp
  2d/CCTransition.cpp
  2d/CCTransitionPageTurn.cpp
  2d/CCTransitionProgress.cpp
  2d/CCTweenFunction.cpp
  2d/CCUserDefault.cpp
  2d/CCUserDefaultAndroid.cpp
  2d/CCVertex.cpp
  2d/TGAlib.cpp
  2d/ccCArray.cpp
  2d/ccUTF8.cpp
  2d/ccUtils.cpp
  2d/platform/CCSAXParser.cpp
  2d/platform/CCThread.cpp
  2d/platform/CCGLViewProtocol.cpp
  2d/platform/CCFileUtils.cpp
  2d/platform/CCImage.cpp
  ../external/edtaa3func/edtaa3func.cpp
)

