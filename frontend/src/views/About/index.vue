<template>
  <div class="about">
    <!-- Hero Section -->
    <div class="hero-section">
      <div class="hero-content">
        <div class="hero-text">
          <h1 class="hero-title">
            Alpha-Agent
            <span class="version-badge">v1.0.0-preview</span>
          </h1>
          <p class="hero-subtitle">
            现代化的多智能体股票分析学习平台
          </p>
          <p class="hero-description">
            基于先进的AI技术，为投资者提供专业、准确、及时的股票分析服务。
            采用多智能体协作模式，从不同角度对股票进行全方位分析，助您做出更明智的投资决策。
          </p>
          <div class="hero-actions">
            <el-button type="primary" size="large" @click="goToAnalysis">
              <el-icon><TrendCharts /></el-icon>
              开始分析
            </el-button>
            <!-- 查看文档按钮已隐藏
            <el-button size="large" @click="viewDocumentation">
              <el-icon><Document /></el-icon>
              查看文档
            </el-button>
            -->
          </div>
        </div>
        <div class="hero-visual">
          <div class="hero-card">
            <div class="hero-stats">
              <div class="stat-item">
                <div class="stat-number">12</div>
                <div class="stat-label">智能体</div>
              </div>
              <div class="stat-item">
                <div class="stat-number">12+</div>
                <div class="stat-label">数据源</div>
              </div>
              <div class="stat-item">
                <div class="stat-number">24/7</div>
                <div class="stat-label">实时监控</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- 核心功能 -->
    <div class="features-section">
      <div class="section-header">
        <h2 class="section-title">核心功能</h2>
        <p class="section-subtitle">强大的AI驱动分析能力，全方位投资决策支持</p>
      </div>

      <div class="features-grid">
        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon primary">
              <el-icon><TrendCharts /></el-icon>
            </div>
            <h3>多智能体分析</h3>
          </div>
          <p>基本面、技术面、新闻分析、社媒分析等12个智能体协作，提供全方位的股票分析视角</p>
          <div class="feature-tags">
            <el-tag size="small">基本面分析</el-tag>
            <el-tag size="small">技术分析</el-tag>
            <el-tag size="small">新闻分析</el-tag>
            <el-tag size="small">社媒分析</el-tag>
          </div>
        </div>

        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon success">
              <el-icon><Search /></el-icon>
            </div>
            <h3>智能股票筛选</h3>
          </div>
          <p>多维度筛选条件，智能算法推荐，快速发现具有投资价值的优质股票</p>
          <div class="feature-tags">
            <el-tag size="small" type="success">多维筛选</el-tag>
            <el-tag size="small" type="success">智能推荐</el-tag>
          </div>
        </div>

        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon warning">
              <el-icon><Files /></el-icon>
            </div>
            <h3>批量分析处理</h3>
          </div>
          <p>支持批量股票分析，并行处理提高效率，适合大规模投资组合分析</p>
          <div class="feature-tags">
            <el-tag size="small" type="warning">批量处理</el-tag>
            <el-tag size="small" type="warning">并行计算</el-tag>
          </div>
        </div>

        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon info">
              <el-icon><Document /></el-icon>
            </div>
            <h3>专业分析报告</h3>
          </div>
          <p>生成详细的分析报告，支持PDF、Excel等多种格式导出，便于分享和存档</p>
          <div class="feature-tags">
            <el-tag size="small" type="info">PDF导出</el-tag>
            <el-tag size="small" type="info">Excel报表</el-tag>
          </div>
        </div>

        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon danger">
              <el-icon><Monitor /></el-icon>
            </div>
            <h3>实时监控</h3>
          </div>
          <p>实时监控分析进度和系统状态，提供详细的任务执行日志和性能指标</p>
          <div class="feature-tags">
            <el-tag size="small" type="danger">实时监控</el-tag>
            <el-tag size="small" type="danger">性能分析</el-tag>
          </div>
        </div>

        <div class="feature-card">
          <div class="feature-header">
            <div class="feature-icon primary">
              <el-icon><Setting /></el-icon>
            </div>
            <h3>个性化配置</h3>
          </div>
          <p>灵活的参数配置和个人偏好设置，支持自定义分析策略和风险偏好</p>
          <div class="feature-tags">
            <el-tag size="small">自定义策略</el-tag>
            <el-tag size="small">风险配置</el-tag>
          </div>
        </div>
      </div>
    </div>

    <!-- 技术架构模块已删除 -->

    <!-- 版本信息模块已删除 -->

    <!-- 联系我们模块及Footer已隐藏
    <div class="contact-section">
      <div class="section-header">
        <h2 class="section-title">联系我们</h2>
        <p class="section-subtitle">获取支持、反馈问题或加入社区讨论</p>
      </div>

      <div class="contact-grid">
        <div class="contact-card">
          <div class="contact-icon email">
            <el-icon><Message /></el-icon>
          </div>
          <h4>邮箱联系</h4>
          <p>hsliup@163.com</p>
          <span class="contact-desc">技术支持和商务合作</span>
        </div>

        <div class="contact-card">
          <div class="contact-icon qq">
            <el-icon><ChatDotRound /></el-icon>
          </div>
          <h4>QQ交流群</h4>
          <p>187537480</p>
          <span class="contact-desc">用户交流和问题讨论</span>
        </div>

        <div class="contact-card">
          <div class="contact-icon wechat">
            <el-icon><ChatDotRound /></el-icon>
          </div>
          <h4>微信公众号</h4>
          <p>Alpha-Agent</p>
          <span class="contact-desc">最新动态和使用教程</span>
        </div>

        <div class="contact-card">
          <div class="contact-icon docs">
            <el-icon><Document /></el-icon>
          </div>
          <h4>使用文档</h4>
          <p>
            <a href="https://mp.weixin.qq.com/s/ppsYiBncynxlsfKFG8uEbw"
               target="_blank"
               rel="noopener noreferrer"
               class="doc-link">
              查看详细文档
            </a>
          </p>
          <span class="contact-desc">完整的使用指南和API文档</span>
        </div>
      </div>
    </div>

    <div class="footer-section">
      <div class="footer-content">
        <p>&copy; 2025 Alpha-Agent. All rights reserved.</p>
        <p>许可证说明：开源组件遵循 Apache 2.0；前端与后端采用专有许可证（个人学习/研究免费，商业使用需授权）。</p>
      </div>
    </div>
    -->
  </div>
</template>

<script setup lang="ts">
import { ref } from 'vue'
import { useRouter } from 'vue-router'
import {
  TrendCharts,
  Search,
  Files,
  Document,
  Monitor,
  Setting,
  Message,
  ChatDotRound,
  Cpu
} from '@element-plus/icons-vue'

const router = useRouter()
const buildTime = ref(new Date().toLocaleString('zh-CN'))

const goToAnalysis = () => {
  router.push('/analysis/single')
}

const viewDocumentation = () => {
  window.open('https://mp.weixin.qq.com/s/ppsYiBncynxlsfKFG8uEbw', '_blank')
}
</script>

<style lang="scss" scoped>
.about {
  max-width: 1000px;
  margin: 0 auto;
  padding: 0 20px;

  // Hero Section - 调浅背景色让标题更清晰
  .hero-section {
    background: linear-gradient(135deg, #334155 0%, #3b82f6 50%, #6366f1 100%);
    border-radius: 16px;
    padding: 40px 32px;
    margin-bottom: 40px;
    color: white;
    position: relative;
    overflow: hidden;
    box-shadow: 0 16px 48px rgba(15, 23, 42, 0.35);

    &::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grain" width="100" height="100" patternUnits="userSpaceOnUse"><circle cx="25" cy="25" r="1" fill="white" opacity="0.03"/><circle cx="75" cy="75" r="1" fill="white" opacity="0.03"/></pattern></defs><rect width="100" height="100" fill="url(%23grain)"/></svg>');
      pointer-events: none;
    }

    .hero-content {
      display: flex;
      align-items: center;
      gap: 40px;
      position: relative;
      z-index: 1;
    }

    .hero-text {
      flex: 1;

      .hero-title {
        font-size: 36px;
        font-weight: 700;
        margin: 0 0 14px 0;
        line-height: 1.2;
        letter-spacing: -0.5px;

        .version-badge {
          display: inline-block;
          background: rgba(255, 255, 255, 0.12);
          padding: 4px 10px;
          border-radius: 16px;
          font-size: 12px;
          font-weight: 500;
          margin-left: 12px;
          backdrop-filter: blur(10px);
          border: 1px solid rgba(255, 255, 255, 0.1);
        }
      }

      .hero-subtitle {
        font-size: 18px;
        font-weight: 500;
        margin: 0 0 14px 0;
        opacity: 0.9;
      }

      .hero-description {
        font-size: 13px;
        line-height: 1.6;
        margin: 0 0 20px 0;
        opacity: 0.75;
        max-width: 480px;
      }

      .hero-actions {
        display: flex;
        gap: 12px;

        .el-button {
          padding: 10px 20px;
          font-size: 13px;
          border-radius: 8px;
          font-weight: 600;
          transition: all 0.3s ease;

          &.el-button--primary {
            background: linear-gradient(135deg, #3b82f6 0%, #2563eb 100%);
            color: white;
            border: none;
            box-shadow: 0 4px 14px rgba(37, 99, 235, 0.4);

            &:hover {
              background: linear-gradient(135deg, #2563eb 0%, #1d4ed8 100%);
              transform: translateY(-2px);
              box-shadow: 0 6px 20px rgba(37, 99, 235, 0.5);
            }
          }

          &:not(.el-button--primary) {
            background: rgba(255, 255, 255, 0.08);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
            backdrop-filter: blur(10px);

            &:hover {
              background: rgba(255, 255, 255, 0.15);
              transform: translateY(-2px);
            }
          }
        }
      }
    }

    .hero-visual {
      .hero-card {
        background: rgba(255, 255, 255, 0.06);
        backdrop-filter: blur(20px);
        border-radius: 12px;
        padding: 24px;
        border: 1px solid rgba(255, 255, 255, 0.1);

        .hero-stats {
          display: flex;
          gap: 24px;

          .stat-item {
            text-align: center;

            .stat-number {
              font-size: 26px;
              font-weight: 700;
              margin-bottom: 6px;
              background: linear-gradient(135deg, #60a5fa, #a78bfa);
              -webkit-background-clip: text;
              -webkit-text-fill-color: transparent;
              background-clip: text;
            }

            .stat-label {
              font-size: 12px;
              opacity: 0.7;
              font-weight: 500;
            }
          }
        }
      }
    }
  }

  // Section Headers
  .section-header {
    text-align: center;
    margin-bottom: 32px;

    .section-title {
      font-size: 26px;
      font-weight: 600;
      color: var(--el-text-color-primary);
      margin: 0 0 10px 0;
    }

    .section-subtitle {
      font-size: 14px;
      color: var(--el-text-color-regular);
      margin: 0;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
    }
  }

  // Features Section
  .features-section {
    margin-bottom: 50px;

    .features-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 16px;

      .feature-card {
        background: var(--el-bg-color);
        border-radius: 12px;
        padding: 20px;
        box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
        border: 1px solid var(--el-border-color-lighter);
        transition: all 0.3s ease;
        position: relative;
        overflow: hidden;

        &::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          right: 0;
          height: 3px;
          background: linear-gradient(90deg, #1e40af, #4338ca);
        }

        &:hover {
          transform: translateY(-4px);
          box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
        }

        .feature-header {
          display: flex;
          align-items: center;
          gap: 12px;
          margin-bottom: 10px;

          .feature-icon {
            width: 40px;
            height: 40px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            color: white;

            &.primary {
              background: linear-gradient(135deg, #1e40af, #3b82f6);
            }

            &.success {
              background: linear-gradient(135deg, #047857, #10b981);
            }

            &.warning {
              background: linear-gradient(135deg, #b45309, #f59e0b);
            }

            &.info {
              background: linear-gradient(135deg, #0369a1, #0ea5e9);
            }

            &.danger {
              background: linear-gradient(135deg, #b91c1c, #ef4444);
            }
          }

          h3 {
            margin: 0;
            font-size: 15px;
            font-weight: 600;
            color: var(--el-text-color-primary);
          }
        }

        p {
          color: var(--el-text-color-regular);
          line-height: 1.5;
          margin: 0 0 12px 0;
          font-size: 13px;
        }

        .feature-tags {
          display: flex;
          flex-wrap: wrap;
          gap: 6px;

          .el-tag {
            border-radius: 10px;
            border: none;
            font-size: 11px;
          }
        }
      }
    }
  }

  // Tech Section
  .tech-section {
    margin-bottom: 50px;

    .tech-stack {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 32px;

      .tech-category {
        background: var(--el-bg-color);
        border-radius: 16px;
        padding: 32px;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        border: 1px solid var(--el-border-color-lighter);
        transition: all 0.3s ease;

        &:hover {
          transform: translateY(-4px);
          box-shadow: 0 8px 30px rgba(0, 0, 0, 0.12);
        }

        .tech-header {
          display: flex;
          align-items: center;
          gap: 16px;
          margin-bottom: 24px;

          .tech-icon {
            width: 48px;
            height: 48px;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            color: white;

            &.frontend {
              background: linear-gradient(135deg, #047857, #1e3a5f);
            }

            &.backend {
              background: linear-gradient(135deg, #b91c1c, #7c2d12);
            }

            &.ai {
              background: linear-gradient(135deg, #6d28d9, #1e40af);
            }
          }

          h3 {
            margin: 0;
            font-size: 20px;
            font-weight: 600;
            color: var(--el-text-color-primary);
          }
        }

        .tech-list {
          .tech-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid var(--el-border-color-extra-light);

            &:last-child {
              border-bottom: none;
            }

            .tech-name {
              font-weight: 500;
              color: var(--el-text-color-primary);
            }

            .tech-desc {
              font-size: 14px;
              color: var(--el-text-color-regular);
            }
          }
        }
      }
    }
  }

  // Version Section
  .version-section {
    margin-bottom: 80px;

    .version-info {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 32px;

      .version-card {
        background: linear-gradient(135deg, #0f172a 0%, #1e3a8a 100%);
        border-radius: 16px;
        padding: 36px;
        color: white;
        position: relative;
        overflow: hidden;
        box-shadow: 0 10px 40px rgba(15, 23, 42, 0.3);

        &::before {
          content: '';
          position: absolute;
          top: -50%;
          right: -50%;
          width: 100%;
          height: 100%;
          background: radial-gradient(circle, rgba(59, 130, 246, 0.15) 0%, transparent 70%);
          pointer-events: none;
        }

        .version-main {
          text-align: center;
          margin-bottom: 24px;
          position: relative;
          z-index: 1;

          .version-number {
            font-size: 48px;
            font-weight: 800;
            margin-bottom: 12px;
            background: linear-gradient(135deg, #60a5fa, #a78bfa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
          }

          .version-status {
            background: rgba(255, 255, 255, 0.12);
            padding: 6px 18px;
            border-radius: 20px;
            font-size: 14px;
            display: inline-block;
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
          }
        }

        .version-details {
          position: relative;
          z-index: 1;

          .version-item {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.08);

            &:last-child {
              border-bottom: none;
            }

            .label {
              opacity: 0.7;
            }

            .value {
              font-weight: 500;
            }
          }
        }
      }

      .framework-info {
        background: var(--el-bg-color);
        border-radius: 16px;
        padding: 36px;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        border: 1px solid var(--el-border-color-lighter);

        h4 {
          margin: 0 0 24px 0;
          font-size: 20px;
          font-weight: 600;
          color: var(--el-text-color-primary);
        }

        .framework-list {
          .framework-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 0;
            border-bottom: 1px solid var(--el-border-color-extra-light);

            &:last-child {
              border-bottom: none;
            }

            .name {
              font-weight: 500;
              color: var(--el-text-color-primary);
            }

            .version {
              background: linear-gradient(135deg, #1e40af, #3b82f6);
              color: white;
              padding: 4px 12px;
              border-radius: 12px;
              font-size: 12px;
              font-weight: 500;
            }
          }
        }
      }
    }
  }

  // Contact Section
  .contact-section {
    margin-bottom: 80px;

    .contact-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 24px;

      .contact-card {
        background: var(--el-bg-color);
        border-radius: 16px;
        padding: 32px;
        text-align: center;
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        border: 1px solid var(--el-border-color-lighter);
        transition: all 0.3s ease;

        &:hover {
          transform: translateY(-4px);
          box-shadow: 0 8px 30px rgba(0, 0, 0, 0.12);
        }

        .contact-icon {
          width: 64px;
          height: 64px;
          border-radius: 16px;
          display: flex;
          align-items: center;
          justify-content: center;
          margin: 0 auto 20px;
          font-size: 24px;
          color: white;

          &.email {
            background: linear-gradient(135deg, #b91c1c, #dc2626);
          }

          &.qq {
            background: linear-gradient(135deg, #0369a1, #6d28d9);
          }

          &.wechat {
            background: linear-gradient(135deg, #047857, #059669);
          }

          &.docs {
            background: linear-gradient(135deg, #1e40af, #4338ca);
          }
        }

        h4 {
          margin: 0 0 12px 0;
          font-size: 18px;
          font-weight: 600;
          color: var(--el-text-color-primary);
        }

        p {
          margin: 0 0 8px 0;
          font-size: 16px;
          font-weight: 500;
          color: var(--el-text-color-primary);

          .doc-link {
            color: #2563eb;
            text-decoration: none;
            font-weight: 500;

            &:hover {
              text-decoration: underline;
            }
          }
        }

        .contact-desc {
          font-size: 14px;
          color: var(--el-text-color-regular);
        }
      }
    }
  }

  // Footer Section
  .footer-section {
    text-align: center;
    padding: 40px 0;
    border-top: 1px solid var(--el-border-color-extra-light);
    color: var(--el-text-color-regular);

    .footer-content {
      p {
        margin: 8px 0;
        font-size: 14px;
      }
    }
  }
}

// 响应式设计
@media (max-width: 1024px) {
  .about {
    .version-section .version-info {
      grid-template-columns: 1fr;
    }
  }
}

@media (max-width: 768px) {
  .about {
    padding: 0 16px;

    .hero-section {
      padding: 40px 24px;

      .hero-content {
        flex-direction: column;
        gap: 32px;
        text-align: center;
      }

      .hero-text {
        .hero-title {
          font-size: 36px;

          .version-badge {
            display: block;
            margin: 16px auto 0;
            width: fit-content;
          }
        }

        .hero-subtitle {
          font-size: 20px;
        }

        .hero-actions {
          justify-content: center;
          flex-wrap: wrap;
        }
      }
    }

    .section-header {
      .section-title {
        font-size: 28px;
      }

      .section-subtitle {
        font-size: 16px;
      }
    }

    .features-section .features-grid {
      grid-template-columns: 1fr;
    }

    .tech-section .tech-stack {
      grid-template-columns: 1fr;
    }

    .contact-section .contact-grid {
      grid-template-columns: 1fr;
    }
  }
}

@media (max-width: 480px) {
  .about {
    .hero-section {
      padding: 32px 20px;

      .hero-text {
        .hero-title {
          font-size: 28px;
        }

        .hero-subtitle {
          font-size: 18px;
        }

        .hero-actions {
          .el-button {
            padding: 10px 20px;
            font-size: 14px;
          }
        }
      }
    }

    .features-section .features-grid .feature-card {
      padding: 24px;
    }

    .tech-section .tech-stack .tech-category {
      padding: 24px;
    }

    .contact-section .contact-grid .contact-card {
      padding: 24px;
    }
  }
}
</style>
