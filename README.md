# The-front-end-study-notes

添加全局时间监听页面的可见状态的变化

const handleVisibilityChange = () => {
      if (document.hidden) {
        pauseAudio('backgroundMusicAudio');
      } else {
        playAudio('backgroundMusicAudio', AudioType.BackgroundMusic);
      }
    }
document.addEventListener('visibilitychange', handleVisibilityChange, false);

子仓库
git submodule update --init --recursive    //下载
git link 子仓库名

