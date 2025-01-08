import requests
from datetime import datetime

# 必应每日壁纸 API 的 URL
BING_API_URL = "https://www.bing.com/HPImageArchive.aspx"

def get_bing_daily_wallpaper():
    """
    获取必应每日壁纸的 URL 和相关信息。

    返回：
    - wallpaper_info: 包含壁纸 URL 和相关信息的字典
    """
    # 设置请求参数
    params = {
        'format': 'js',  # 返回 JSON 格式的数据
        'idx': 0,        # 0 表示今天的壁纸，1 表示昨天的壁纸，依此类推
        'n': 1           # 返回的图片数量
    }

    # 发送 GET 请求
    response = requests.get(BING_API_URL, params=params)
    response.raise_for_status()  # 检查请求是否成功

    # 解析响应 JSON 数据
    data = response.json()
    image_data = data['images'][0]
    
    # 构建壁纸信息
    wallpaper_info = {
        'url': "https://www.bing.com" + image_data['url'],
        'title': image_data.get('title', 'Bing Daily Wallpaper'),
        'description': image_data.get('copyright', 'Bing')
    }

    return wallpaper_info

if __name__ == "__main__":
    # 获取必应每日壁纸信息
    wallpaper_info = get_bing_daily_wallpaper()
    
    # 打印壁纸信息
    print("Bing Daily Wallpaper URL:", wallpaper_info['url'])
    print("Title:", wallpaper_info['title'])
    print("Description:", wallpaper_info['description'])