# android-problem
整理android出现的古怪的地方

DialogFragment
当点击虚拟或物理返回键时候DialogFragemnt消失，不调用dismiss方法
DialogFragemnt消失的生命周期是onDismiss->onDestroyView->onDestroy->onDetach


