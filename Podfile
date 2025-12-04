platform :ios, '12.0'

# 全局 pod 定义，供多个 target 继承
abstract_target 'MessageJudgeShared' do
  # 共享的 pods
  pod 'YYModel'
  pod 'Masonry'
  pod 'XLForm', '~> 3.0'

  target 'MessageJudge' do
    # 只针对 MessageJudge 的 pods 可以在这里添加（目前没有额外）
  end

  target 'MessageJudgeExt' do
    # 只针对 MessageJudgeExt 的 pods 可以在这里添加（目前没有额外）
  end

  target 'MessageJudgeTests' do
    inherit! :search_paths
    # 测试相关 pods
  end
end
